# 部署xxxx

## 环境搭建

可使用国内镜像 `https://npm.taobao.org/`

```
# 安装全局 gitbook，root 用户执行
npm install gitbook-cli -g
# 安装本地模块
npm install
# 安装 gitbook 模块
gitbook install
```

## 更新文档

```
git pull
gitbook build
rm -rf _book_cache
cp -r _book _book_cache
```

## test1
## test2
## test3
## test4
## test5
