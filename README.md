summit.g0v.tw
============
Structure adopted from g0v.tw

# Directory structure

 * app: 網頁程式
 * md: 網頁文章

# Required

- Install nodejs
- Install npm 

# Developer

第一次請先執行

    $ npm install

安裝完之後打以下指令跑起 local web server

    $ npm start

然後在 browser 輸入 [http://localhost:3333](http://localhost:3333)

gulp 會自動幫你 compile jade to html, less to css, 合併 javascript, css 等。在更改任何一個檔案 gulp 也會幫你重新 compile。

# Deploy

請打

    $ ./deploy <git remote

# License

MIT http://g0v.mit-license.org
