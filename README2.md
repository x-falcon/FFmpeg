RTMP H265 FFmpeg README
=============

## 推流
ffmpeg -re -i 265-hi-03-40-33.mp4  -vcodec libx265 -acodec aac -f flv rtmp://127.0.0.1:1935/live/steam
