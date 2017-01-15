 oose_-0324027-資管3A 0324027 蔡益嘉(組長)：工作分配、分組討論內容、資料庫撰寫
 
 oose_-0324029-資管3A 0324029 曾韻文：上傳GitHub、分組討論內容、使用者介面設計
 
 oose_-0324035-資管3A 0324035 江秉軒：分組討論內容、功能製作
 
# 一.文字描述
 
NFC打卡系統

傳統公司都是使用打卡機進行員工的上下班紀錄，有了這套系統，只要擁有NFC功能的手機或平板就能代替打卡機進行上下班紀錄。

功能：

1.管理員可設定上下班時間，讓員工進行打卡

2.管理員可依照時間或員工姓名查詢打卡紀錄，了解員工的出缺勤

3.管理員可新增、修改、刪除員工的資料

4.管理員可進行系統設定 ex:修改密碼等

# 二.圖形介面
![image](https://cloud.githubusercontent.com/assets/22362815/20486990/b811c686-b03c-11e6-9e15-f22496bf7387.jpg)

# 三.功能分析
使用個案名稱: 密碼設定
行為者:管理員
目標:讓管理端設定往後所使用的帳號密碼
結束狀態:系統驗證身分成功，進入管理端

正常程序:
1.	管理員登入系統後端
2.	系統驗證管理員帳號密碼
3.	系統驗證登入成功

例外狀況:
密碼不正確，驗證失敗


使用個案名稱: 員工密碼設定
行為者:員工
目標:讓管理端設定往後所使用的帳號密碼
結束狀態:系統驗證身分成功，進入管理端

正常程序:
1員工登入打卡系統
2.系統驗證員工帳號密碼
3.系統驗證登入成功

例外狀況:
密碼不正確，驗證失敗
 

使用個案名稱:打卡
行為者:員工
目標:紀錄今日上班時間，並確認今日將要完成的事項
結束狀態:打卡完成

正常程序:
1.	員工登入打卡系統，進入打卡畫面
2.	進行打卡動作並檢視公司今日賦予的任務
3.	完成打卡動作開始進行今日工作
例外狀況
超過可打卡時間，仍可進行打卡，但是會留下紀錄


使用個案名稱:人員管理
行為者:管理員，員工
目標:新增或刪除員工名單
結束狀態:完成更改

正常程序:
更改員工名單及個人資料
檢視員工出缺勤情況
修改員工出缺勤情況(管理員限定)
例外狀況
員工不慎於上班時打卡下班
(由管理員確認並進行修改)

# 四.使用個案圖+活動圖
![image](https://cloud.githubusercontent.com/assets/22362815/19692360/45fcd5fa-9b0a-11e6-82ce-626e3181a043.jpg)

# 五.強韌圖
![image](https://cloud.githubusercontent.com/assets/22362815/20487029/dad311e8-b03c-11e6-95ae-9dcc675e2efe.jpg)

# 六.循序圖
![image](https://cloud.githubusercontent.com/assets/22362815/20716291/ab8e2cd2-b68c-11e6-96ba-183ac76279bf.jpg)

# 七.類別圖
![image](https://cloud.githubusercontent.com/assets/22362815/21285791/6df44eac-c47d-11e6-83ce-98711f61a17d.jpg)

# 八.元件圖
![image](https://cloud.githubusercontent.com/assets/22362815/21963595/eb42a3ec-db78-11e6-8ef3-b8b82ff36112.jpg)

# 九.初步APP介面

首頁

![image](https://cloud.githubusercontent.com/assets/22362815/21963600/eb4a84a4-db78-11e6-813b-97211bb8d221.png)

打卡

![image](https://cloud.githubusercontent.com/assets/22362815/21963596/eb434eaa-db78-11e6-8f5d-85544590e4cd.png)

記錄管理

![image](https://cloud.githubusercontent.com/assets/22362815/21963598/eb479ee2-db78-11e6-9b85-410392ff801a.png)

人員管理

![image](https://cloud.githubusercontent.com/assets/22362815/21963599/eb48cb00-db78-11e6-8b8b-101201315fa7.png)

系統設定

![image](https://cloud.githubusercontent.com/assets/22362815/21963597/eb43e3ba-db78-11e6-963d-af610ee10acc.png)
