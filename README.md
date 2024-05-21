# openai-deployment-app-quickstart
## 主要命令：
```
pip install streamlit openai python-dotenv

nohup sudo streamlit run app.py --server.port 80 > my.log 2>&1 &

```

## 其他Tips：
```
Vultr VPS的问题：创建VPS后无法访问80端口。

解决方法：检查防火墙是否拦截了访问，如果是，则使用ufw allow 80命令开放端口。
```
