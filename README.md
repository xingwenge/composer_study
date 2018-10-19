![image](http://xwgimg.nos-eastchina1.126.net/upload/20181016204208.png)

## github
创建github仓库，clone到本地，创建初始化文件

- README.md
- .gitignore

通过"SourceTree"软件提交git代码

## composer
```
$ composer init # 生成composer.json

{
    "name": "xingwenge/composer_study",
    "description": "learning composer",
    "type": "project",
    "license": "MIT",
    "authors": [
        {
            "name": "xingwenge",
            "email": "470703808@qq.com"
        }
    ],
    "require": {}
}
```

### 安装包
```
vi composer.josn
require里增加

composer install
```
## 软件包仓库 packagist
https://packagist.org/

submit package

### 设置自动