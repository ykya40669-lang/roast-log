YOKO Roast Log v8 — Androidのホーム画面に置く手順

このフォルダの中身（index.html / manifest.webmanifest / sw.js / icons）を、
HTTPSで公開できる場所にそのまま置くと、Androidのアプリとしてインストールできます。

■ GitHub Pagesで公開する（無料・スマホのブラウザでも可）
1. github.com で新しいリポジトリを作る（例：roast-log、Public）
2. 「Add file」→「Upload files」で、このフォルダの中身をすべてアップロード
   （iconsフォルダも含める。index.html がリポジトリの一番上に来るように）
3. Settings → Pages → Branch を「main」「/(root)」にして Save
4. 1〜2分後に https://<ユーザー名>.github.io/roast-log/ が開けるようになる

■ Androidにインストールする
1. PixelのChromeで上のURLを開く
2. 画面上の「ホーム画面にアプリとして追加」→「インストール」
   （出ないときはChromeの︙メニュー →「アプリをインストール」）
3. ホーム画面とアプリ一覧にアイコンが追加され、全画面・オフラインで使えます

■ 更新するとき
新しい index.html と sw.js を同じ場所に上書きアップロードするだけです。
記録は端末内に残ったまま、次に開いたときから新しい版になります。

■ 記録の引っ越し
claude.ai版や旧版の記録は、旧版で「バックアップを書き出す」→
新しいアプリで「バックアップをファイルから読み込む」で移せます。

■ AIアドバイス
・claude.ai上で開いたときは、設定なしで「AIに聞く」が使えます。
・インストールしたアプリでは、「好み・機材」の最後にAnthropicのAPIキーを入れると使えます
  （キーはこの端末にだけ保存。API利用料がかかります）。
・キーなしでも「相談用にコピー」でClaudeアプリに貼り付けて相談できます。
