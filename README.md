# RubyArrayNew
Arrayクラスのnewメソッド

## 処理
Arrayクラスのnewメソッドを使って配列を出力する。

## コード
```
numbers = Array.new(4).map{Array.new(3, 1)}
numbers[0][2] = 2
p numbers
```

## 出力結果  
```
[[1, 1, 2], [1, 1, 1], [1, 1, 1], [1, 1, 1]]
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Ruby 2.4.0 |
