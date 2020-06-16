# image_AnomalyDetection

## 画像の異常検知
Dense SIFTで特徴量を作成し、query画像の各特徴量とdatabase画像の各特徴量の距離の最小値を可視化し、異常部分を推定する。

### 参考
- [【OpenCV】OpenCV3以降でDense SIFTを使いたい](http://ni4muraano.hatenablog.com/entry/2018/09/14/232746)
- https://www.cvl.iis.u-tokyo.ac.jp/class2016/2016w/papers/1.time-varyingImageProcessin/Detecting_Irregularities_in_Images_and_in_Video_(ICCV_2005).pdf

### 環境作成
dockerコンテナ作成、起動する。
```
cd c:/Users/user01/work/opencv
#docker build -t jupyterlab-opencv:1.0 .
docker-compose up -d
```

### 接続
http://localhost:8888/
