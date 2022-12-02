# marp-yumekiti-theme

Marp yumekiti Theme is a theme for [Marp](https://marp.app/).

## 使用例

|||
|-|-|
| ![](./assets/headline-example.png) | ![](./assets/general-example.png) |


## 使い方

VS Code の設定で `markdown.Marp.themes` と検索し追加ボタンで `https://raw.githubusercontent.com/yumekiti/slides/main/style.css` を追加する

## サーバー起動方法

```bash
docker run --rm -v $PWD:/home/marp/app/ -e LANG=$LANG -p 8080:8080 marpteam/marp-cli ./ --server
```