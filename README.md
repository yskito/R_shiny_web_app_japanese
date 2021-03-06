---

### このリポジトリは何？
このリポジトリでは、webアプリを開発するためのRファイルを管理しています。  
R shinyパッケージを用いています。
日本語バージョンになります。  

---

### どうやってソースコードをダウンロードするの？
ご希望のフォルダをzipファイルとして丸ごとダウンロードされてください。  
  
ちなみに、おすすめのダウンロード方法は、以下の通りです。  
手順１：　ブラウザchromeで[今のページ](https://github.com/yskito/R_shiny_web_app_japanese)を開く。  
手順２：　GitZip for github(注釈１,２)で、ご希望のフォルダをzipファイルとして丸ごとダウンロードする。  

注釈１：　まだGitZip for githubを追加されていない方は、[こちら](https://gitzip.org/)からchromeに追加してください。  
注釈２：　GitZip for githubの使い方がわからない方は[こちら](https://baba-s.hatenablog.com/entry/2019/09/09/070800)から。  

※githubに普段から慣れていらっしゃる方は、ご自身のお好きな方法でソースコードを取得されてください。

---

### ソースコード取得後はどうすればwebアプリと同じような操作ができるの？
手順１：　ダウンロードしたzipファイルを開く。    
手順２：　ui_server.Rファイルを、ソフトウェアRstudio（注釈１）で開く。  
手順３：　▶︎ Run Appを押す(真ん中上部にあると思います)。  
たった3つのステップで、皆様のPC画面でwebアプリと同様の操作ができます。  
  
注釈１：　ソフトウェアRstudioをお持ちでない方は、[こちら](https://rstudio.com/products/rstudio/download/)からダウンロードできます。無料です。  

---

### 普段からshinyパッケージを用いてwebアプリを開発されている方々へ。ご留意点
通常shinyパッケージを用いたRファイルは、ui.Rとserver.Rで構成されます。  
しかし、分量が多くなると非常に可読性が低下し理解しにくくなります。  
私もui.Rとserver.Rに分離してこれまで試みましたが、分量が多くなるとわかりにくいと感じました。  
  
そのため、このリポジトリにあるRファイルは両方の内容を含み、その他のRファイルから構成されます。  
この点にはご留意いただければ幸いです。
なお、shinyApp(ui,server)とすれば実装できます。

---

この箇所のみ、テストです。
