# 感谢原作者
我做了一些简单的改动（添加指向图片资源的接口），同时上传了大概1000张张vv老师的表情包在/vv_image里

于是我们现在可以调用这个api来搜索vv表情包了

原readme如下：

你願意一輩子跟我一起MyGo嗎？
[API Swagger Docs](https://mygoapi.miyago9267.com/docs)

## 部署

### 環境變數

僅有設定啟動PORT 預設為3030

### 安裝及啟動

```bash
git clone https://github.com/miyago9267/mygoapi.git && cd mygoapi
poetry install
poetry run python3 mygo/app.py
```

## License

本專案採MIT License
歡迎fork進行修改、PR、二次開發
