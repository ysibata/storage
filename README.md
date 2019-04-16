# vippool-storage

このプロジェクトは、株式会社 VIPPOOL が運用している
vippool-clerk サービスへアクセスすることで、
Python から簡単にモナコインのブロックチェーンへの
データ書き込み・読み込みができるライブラリです。

## できること

1. 秘密鍵に対応するコインアドレスの、現在の残高を知ることが出来ます。
2. 秘密鍵に対応するコインアドレスから、別のコインアドレスへ送金することができます。
3. ブロックチェーンに任意のデータ列を書き込むことができます。（別途トランザクション手数料が必要です）。
4. ブロックチェーンに書き込まれた任意データを読み込むことができます。

## インストール方法

pip を用いてインストールが可能です。

> $ pip install vippool_storage

## 使用方法

リポジトリの [sample.py](sample.py) をご覧ください。

## 連絡先

お問い合わせ、ご要望、バグ報告等は、github の issue へお気軽にどうぞ。  
https://github.com/vippool/storage/issues

もしくは、開発チームまでメールいただいても構いません。  
dev-team@vippool.net

## ライセンス

(C) 2019-2019 VIPPOOL Inc.

このプロジェクトは、MIT ライセンスで提供されます。
