# pdf_to_deepl_for_chrome

## 使い方

1. `pdf_to_deepl_for_chrome.exe`をダウンロードし、実行しておく。
2. `Win+C`で選択した文字列の改行を取り除いたうえで DeepL アプリに入力する。

![](img/deepl3.gif)

## 前提

- DeepL をインストール済みで、Ctrl+C×2 で起動する設定が有効になっていること

## PC 起動時に自動で起動する方法

1. `pdf_to_deepl_for_chrome.exe`を右クリックしてショートカットを作成する
2. 作成したショートカットを`C:\Users\<user_name>\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup`に置く

## exe をダウンロードしたくない人向け

[AutoHotkey](https://www.autohotkey.com/)をインストールして`pdf_to_deepl_for_chrome.ahk`を実行する

# 免責事項

当スクリプトの実行は自己責任でお願いします。特に、AutoHotkey を悪用した攻撃が過去に確認されています。[トレンドマイクロ、キー操作自動化ツール「AutoHotkey」を悪用した攻撃を確認・警告](https://forest.watch.impress.co.jp/docs/news/1178824.html)
