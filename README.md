# 無機化学総論
## 機能
目次の各項目から各ページに飛ぶことができます。
### 無機化学
左下の`無機化学`を押すと目次に戻ります。
```
\newcommand{\hl}[1]{\underline{\textcolor{red}{\gtfamily #1}}}
\newcommand{\hce}[1]{\textcolor{blue}{¥ce{#1}}}
\newcommand{\hlbox}[1]{\fbox{\textcolor{red}{\gtfamily #1}}}
```
内の`red`や`blue`の値を`white`にしたり、
```
\newcommand{\hl}[1]{\underline{\textcolor{white}{\gtfamily #1}}}
```
`\phantom`などで囲むことで空欄にできます。
```
\newcommand{\hl}[1]{\underline{\phantom{\gtfamily #1}}}
```
前者だと改行が反映されますが、テキスト自体が白になっているだけなので選択することがきてしまいます。後者だとテキスト自体は隠れますが、改行が反映されません。
`\hl`は下線付きの赤くなっている文字、`\hce`は青で表示されている化学式、`\hbox`は視覚で囲まれている構造式・電子式です。

## 内容
### 無機化学
無機化学のテキストを少し変更したもの

[PDF](/無機化学/inorganic-chemistry.pdf)／
[ソースコード](/無機化学/inorganic-chemistry.tex)
### 反応式
無機化学のテキストから化学式のみを取り出したもの

[PDF(赤シート用)](反応式/反応式まとめ[赤シート用].pdf)／
[PDF(書き込み用)](反応式/反応式まとめ[書き込み用].pdf)／
[ソースコード](/反応式/反応式まとめ.tex)

## 使用しているパッケージ
- amsmath
- ascmac
- chemfig
- color
- enumerate
- fancyhdr
- hyperref
- lastpage
- lscape
- mhchem
- multicol
- multirow
- tikz
- xcolor

化学式は全て`mhchem`を使用しています。電子式などは`chemfig`を利用しています。
PDF内のジャンプ用に`hyperref`を使用しています。
