# android-codelab-restapi-retrofit-moshi-coil

Introduction
------------
- Android CodeLabで作ったアプリです。
- アプリ名称: MarsPhotos
- インターネットから火星の写真のURLを取得し、画像をダウンロードし表示するアプリです。
  
対象Codelab
------------

### インターネットからデータを取得する ###
https://developer.android.com/codelabs/basic-android-kotlin-training-getting-data-internet?hl=ja  
- Retrofit (REST ウェブサービス)
- Moshiライブラリ (JSON 解析)
  
### インターネットから画像を読み込んで表示する ###
https://developer.android.com/codelabs/basic-android-kotlin-training-internet-images?hl=ja
- Coilライブラリ (画像のダウンロード、バッファリング、デコード、キャッシュ保存)
- BindingAdapter (Statusデータが変更されたときのViewのカスタム動作を提供)
- RecyclerView
- GridLayoutManager
  
### ネットワーク リクエストをテストする ###
https://developer.android.com/codelabs/android-basics-kotlin-test-network-request?hl=ja
- オブジェクト指向プログラミングをテストに適用する方法
- テスト ディレクトリにリソースを格納する方法
- テストで suspend 関数を呼び出す方法
- テストで API レスポンスをモックする方法
  
アプリ画面
----  
### 静止画 ###
<img src="https://github.com/zono345/android-codelab-restapi-retrofit-moshi-coil/blob/master/readme_file/screen_01.png" width="100%">
  
  
### GIF ###  
**アプリ**  
|Internet On|Internet Off|
|---|---|
|<img src="https://github.com/zono345/android-codelab-restapi-retrofit-moshi-coil/blob/master/readme_file/internet_on.gif" width="74%">|<img src="https://github.com/zono345/android-codelab-restapi-retrofit-moshi-coil/blob/master/readme_file/internet_off.gif" width="50%">|

**テスト: MarsApiServiceTests**  
<img src="https://github.com/zono345/android-codelab-restapi-retrofit-moshi-coil/blob/master/readme_file/readme_mars_movie_test.gif" width="100%">
