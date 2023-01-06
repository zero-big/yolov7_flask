# yolov7_flask
##Description
  1. yolov7 모델을 활용하여 철스크랩, 병, 캔을 분류모델을 제작
  2. flask로 웹페이지를 만들고 사진을 올리면 판별하도록 진행

##Process
1. roboflow를 활용하여 라벨링 진행
  - <img src="img/roboflow.jpg">
  - 데이터의 양이 적어서 수평, 수직으로 변형을 주어 학습량을 늘림

2. 가중치를 YOLOv7-X로 주고 학습을 진행
  - 라벨링 데이터의 이미지사이즈에 맞춰 가중치가 좋은 YOLOv7-X를 사용(기본은 VOLOv7)
 
3. 커스텀 데이터셋으로 만든 가중치를 통해 예측 진행

4. flask의 기본 웹페이지 제작 후 html작성
  - 
