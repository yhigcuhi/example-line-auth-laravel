# example-line-auth-laravel
Laravelによる LINE関連の ログインの色々お試し

## 目的
- LINE ログイン かつ 公式LINE友だち追加 の実装

## 環境構築時での 手順 (プロジェクトを新規作成する時の手順)
1. Docker 用意
1. コンテナ起動
1. composer create-project laravel/laravel .
1. composer require laravel/breeze --dev
1. curl https://www.toptal.com/developers/gitignore/api/vim,react,node,linux,macos,laravel,windows,composer,intellij,sublimetext,visualstudio,visualstudiocode >> .gitignore
1. php artisan breeze:install react --typescript

## 参考
- [LaravelとLINEの連携：LINEでLaravelにログイン機能搭載](https://biz.addisteria.com/laravel_line_integration/)
- [Laravel9 Socialite LINEログイン実装](https://qiita.com/takahara_yuuki/items/6b84330582e69ed0b297)
- [composer socialiteproviders/line パッケージについて](https://packagist.org/packages/socialiteproviders/line)