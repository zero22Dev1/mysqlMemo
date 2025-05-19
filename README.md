# mysqlMemo
📝：Mysqlのメモ


#環境構築(Mac)

Homebrewがインストールされているかの確認
``` cmd
brew --version
```
インストールされていなかったら下記のコマンド
``` cmd
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

``` cmd

brew install mysql

```

#権限付与

``` sql
GRANT SELECT ON my_schema.customers TO 'readonly_user'@'localhost';

```