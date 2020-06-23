# hello-world

このプロジェクトは、私が最初にGitHubを使った時に作成したチュートリアルです。

## 概要

このチュートリアルは、リポジトリの基本的な操作について [GitHubガイド](https://guides.github.com/)に掲載されている[HelloWorld](https://guides.github.com/activities/hello-world)に従って説明します。チュートリアルを完了するには、GitHubのアカウントと以下のクライアント環境が必要です。GitクライアントにはEclipseを使用します。

クライアント環境

- Windows10 Pro
- Eclipse 2019-12 Version 4.14

リンク
- [https://github.com/](https://github.com/) --- GitHubの本家
- [https://guides.github.com/](https://guides.github.com/) --- GitHubガイド
- [リポジトリの作成、クローン、アーカイブ](https://help.github.com/ja/github/creating-cloning-and-archiving-repositories) --- GitHubヘルプより
- [リポジトリを管理する](https://help.github.com/ja/github/administering-a-repository) --- GitHubヘルプより
- [Hello World](https://guides.github.com/activities/hello-world/) --- GitHubガイドより

## GitHubフロー

以下では、[GitHubガイド](https://guides.github.com/)の[HelloWorld](https://guides.github.com/activities/hello-world)に従って説明を進めます。HelloWorldは、README.mdを編集するだけの簡単な例題ですが、GitHubの基本的なワークフローを理解する上では十分なものです。

まず最初に、新しいリポジト( hello-world )作ります。GitHubでは、リポジトリ作成直後は、デフォルトでmasterブランチが作成されます。そして、README.md編集用のブランチ( readme-edits )を追加します。README.md の編集作業はこのブランチで行います。作業終了後に、プルリクエストを開きコードの変更をレビュワー(ここではリポジトリのオーナー)に通知します。レビューが終わると、readme-edits ブランチをmasterブランチにマージします。

このように、GitHubの機能単位の作業は、ブランチ作成、コード編集、プルリクエスト、コードレビュー そして マージの順に進行していきます。この流れは、[GitHub Flow](https://help.github.com/ja/github/collaborating-with-issues-and-pull-requests/github-flow)と呼ばれ、GitHubでのワークフローモデルになっています。

参考リンク

- [GitHubフロー](https://help.github.com/ja/github/collaborating-with-issues-and-pull-requests/github-flow) --- GitHubヘルプより
- [GitHubフローを理解する](https://guides.github.com/introduction/flow/) --- GitHubガイドより
- [GitHub Flow](http://scottchacon.com/2011/08/31/github-flow.html) --- Scott Chacon on the Interwebs
- [GitHub Flow](https://gist.github.com/Gab-km/3705015) --- Scott Chacon on the Interwebs(邦訳)<br>Scott Chacon(スコット・チャコン氏)はGitのエバンジェリストでGitHubのスタートに携わった人物

## 続きは

こちらをご覧ください。

[GitHub リポジトリの基本操作](http://www.y2sunlight.com/ground/doku.php?id=github:basic) --- y2sunlight.com
