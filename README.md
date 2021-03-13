# BuyHomeLogin
<h1>購物車專題</h1>
<h6>(最終修定版本合併至作者群betty8398)</h6>
<p>
作者群：Lucien-Hsu、betty8398、wubrother18<br>

日期：2020/12/22

<h2>動機與目的</h2>
使用原生App製作購物車能使用到各式各樣技術。市面上的購物車App 大多因為顏色過多或商品名稱過長而導致使用者難以快速掌握到畫面上的資訊。
我們的目標是做出版面簡潔舒服，且擁有購物功能的原生Android App。

<h2>開發環境與使用平台</h2>

Android Studio<br>
使用版本：4.0.1<br>
模擬器：Pixel4 API29<br>

Firebase<br>
使用Firebase 的 Realtime Database，參考官方推薦，只需要簡單的查詢和單一JSON樹所以我們選擇Realtime Database而非Cloud Firestore。<br>

Figma<br>
採用Figma製作Wireframe、Mockup、Prototype。<br>
Wireframe能在黑白線框下，聚焦在粗略的概念設計，減少考慮色彩或詳細排版的雜訊。<br>
Mockup建立在能在Wireframe基礎上，討論詳細的版面與顏色呈現。<br>
Prototype可已呈現使用者點按、滑動後所呈現的效果。<br>
這些都可以幫助我們進到Android Studio之前有具體的呈現共識。<br>

Git / GitHub<br>
採用GitHub Flow方式進行版本管理與協作。<br>


<h2>專題成果</h2>

閃頻頁：<br>
給使用者的第一印象，
呈現主題logo，以天藍色為色調，
帶給使用者輕鬆愉悅的使用體驗。

商品展示頁：<br>
使用ViewPager、RecyclerView、NetworkImageView
等元件，帶給使用者高效、快速且豐富的使用體驗，
除了提升程式穩定性，
也帶給使用者更良好的使用感受，
提升購買慾望。

商品詳細內容頁面：<br>
此頁面呈現單一商品的詳細資料，
實品照片、賣家的詳盡描述，
點亮愛心、社群通訊的分享功能，
讓使用者能與人群有更多的互動，
推廣商品與本應用程式的同時，
也獲得了實際的參與感。
醒目的「心動」按鈕，
直覺化的加入購物中設計，
必然能大大強化使用者的購買意願。

評論頁：<br>
顯示所有相關的評論，
並附帶篩選功能，
如果有登入帳號，
還可能在此留下自己的足跡，
與人一同分享喜悅。

地圖頁：<br>
透過Google Map，可以得知商家的實際所在，
對於想得知更多賣家資訊，
又或是採用面交選項的買家，
實在再方便不過了。

分類頁面：<br>
此處提供不同類別的篩選，
讓使用者從海量的商品中，
更容易找到中意的商品。

專屬頁面：<br>
全名「專屬優惠頁面」
提供專屬於使用者、
專屬於這個時區、時段的，
限量、限時商品，
可以說是使用者最期待的專區了，
還有小彩蛋喔~

登入頁面<br>
上方是註冊過的會員輸入帳號密碼，按下藍色登入按鈕可以進行登入。
藍色按鈕下方有google登入按鈕會連接到google登入流程。
最右下角藍色字Register可以前往註冊頁面。

註冊頁面<br>
由上而下分別是使用者姓名、帳號(email)、密碼、確認密碼。<br>
按下Sign Up會進行註冊格式檢查<br>
1. email 必須含有@<br>
2. 密碼長度不可小於5<br>
3. 確認密碼必須和密碼一致<br>
確認格式後會進行線上firebase realtime database會員資料比對，若沒有此使用者註冊過(以email為主)則會註冊註冊成功
最右下角Sign in 可以回到登入頁面<br>


選擇google登入會跳出google做好的api<br>
可以選擇其他app有登入過的google帳號<br>
使用firebase註冊過的會員登入成功<br>
的轉場畫面<br>

個人頁面<br>
可設定宅配地址、取貨門市、付款方式。<br>

個人資訊頁面<br>
大頭照可以進行編輯。<br>
能選擇從相簿取得相片或是相機直接拍攝照片。<br>

購物車頁面<br>
加減符號可以調整商品數量<br>
同時下方小計金額會即時更動<br>

每項商品右上角都有垃圾桶可以做刪除商品<br>


結帳頁面<br>
輸入優惠碼<br>

輸入正確則會變成綠色框框。<br>
並且在下方折抵特定金額。<br>

選擇使用google pay 線上付款<br>




可以新增信用卡<br>

如果是用google 登入會有個人姓名和地址預先填入表格<br>

選擇要付款的信用卡<br>

按下Pay進行付款<br>

成功付款，這裡因為是測試版本，不會實際支付。<br>

按下OK就會回到購物車流程之前的頁面<br>





<h2>未來方向</h2>
修正bug
優化使用者體驗
增加帳戶email驗證和忘記密碼功能
流量控制
商品庫擴充
以 View Binding、Data Binding 提升 App 效能
上架google play

<h2>參考文獻</h2>
Udacity 教學學程：https://classroom.udacity.com/<br>
Android DeepLink介紹與使用: <br>
https://www.itread01.com/content/1545444921.html<br>
Material design：<br>
https://material.io/<br>
GitHub：https://github.com/<br>
三種版控流程：<br>
https://medium.com/@lf2lf2111/%E4%B8%89%E7%A8%AE%E7%89%88%E6%8E%A7%E6%B5%81%E7%A8%8B-29c82f5d4469<br>
Figma：https://www.figma.com/<br>
Jetpack：https://developer.android.com/jetpack<br>
Diagram :  https://www.diagrams.net/<br>
Android Navigation 學習筆記(一) 基礎使用：https://medium.com/@wsrew2000/android-navigation-學習筆記-一-基礎使用-3c1607ce4d38<br>
老灰鴨的筆記本：https://oldgrayduck.blogspot.com/2016/06/android-studiogoogle-app.html<br>
[GIT101 心得/筆記] GitHub 操作 -push , pull, clone , fork：<br>
https://medium.com/@brad61517/git101-%E5%BF%83%E5%BE%97-%E7%AD%86%E8%A8%98-github-%E6%93%8D%E4%BD%9C-push-pull-clone-fork-a414d4af64be<br>
[教學] 使用 GitHub Pages + Hexo 來架設個人部落格：<br>
https://ed521.github.io/2019/07/hexo-install/<br>
程式幼幼班：<br>
https://medium.com/程式幼幼班/android筆記-專題筆記02-cardview做圓形頭像-scaletype-c940a42238ba<br>
stackoverflow：<br>
https://stackoverflow.com/questions/28841513/find-fragment-in-fragment<br>
https://stackoverflow.com/questions/59290968/you-must-call-setgraph-before-calling-getgraph<br>
itread01：<br>
https://www.itread01.com/content/1546533917.html<br>
https://www.itread01.com/content/1545444921.html<br>
程式前沿：<br>
https://codertw.com/android-%E9%96%8B%E7%99%BC/343904/<br>
https://codertw.com/android-%E9%96%8B%E7%99%BC/331123/<br>
Simplifiedcoding：<br>
https://www.simplifiedcoding.net/android-volley-example-to-load-image-from-internet/<br>
Google Codelabs：<br>
https://codelabs.developers.google.com/<br>
Android Volley详细解析（一）：Volley基本用法：<br>
https://blog.csdn.net/a553181867/article/details/51226801<br>

宅貓筆記 把Android App上架到Google Play商店：<br>
http://housecatnotes.blogspot.com/2018/05/android-android-appgoogle-play.html<br>
Day30 Android animation 總結：<br>
https://ithelp.ithome.com.tw/articles/10209643<br>
Android Developers：<br>
https://developer.android.com/guide/fragments?hl=zh-tw<br>
Google Pay 付款功能指南：<br>
https://developers.google.com/pay/api/android/guides/setup?hl=zh-tw<br>
Offer simpler and secure payments with Google Pay：<br>
https://developers.google.com/learn/pathways/google-pay#codelab-/codelabs/pay-android-checkout<br>
Use Cases：<br>
https://www.usability.gov/how-to-and-tools/methods/use-cases.html<br>
104人力銀行：<br>
https://www.104.com.tw/job/5uxzj?jobsource=n104bank2<br>

參考書籍：<br>
湯餅翰(2016)。《Android 高效入門>>深度學習 使用 AndroidStudio2開發 Android 6.0 APP》。新北市：博碩文化。<br>
孫宏明(2019)。《Android 程式設計入門應用到精通》。臺北市：碁峰資訊。<br>
洪錦魁(2018)。《Java 入門邁向高手之路 王者歸來》。臺北市：深石數位。<br>
李允中(2013/7/1)。《軟體工程 Software Engineering》。臺灣軟體工程學會。<br>
<br>


