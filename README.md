# NgrokConfig
ngrok的内网客户端配置


## [ngrok](http://ngrok.com) 隧道顺序部分
|资源|用途|
|---|---|
|[dsm.yml](dsm.yml)| 群晖 |
|[rasp.yml](dsm.yml)| pi |

需要先汇入授权码

启用命令
```
./ngrok start -config rasp.yml --all
```

- managet
  - http
  - https
  
- 4040

- webdav

- ssh

## [lu8](http://lu8.top) 部分
### ngrok
|资源|用途|
|---|---|
|[lu8-ngrok-dsm.yml](lu8-ngrok-dsm.yml)| 群晖 |
|[lu8-ngrok-rasp.yml](lu8-ngrok-rasp.yml)| pi |



启用命令
```
./ngrok -config=lu8-ngrok-rasp.yml start-all
```


