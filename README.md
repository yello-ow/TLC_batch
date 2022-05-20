<div align="center">
  <h1> Spark, Ariflow를 이용한 데이터 엔지니어링 Project </h1>
  택시요금 예측을 위한 대용량 데이터 파이프라인 구축 
  <br><br>
  <img src="https://user-images.githubusercontent.com/86868063/169347042-777d13d4-61a5-4850-9673-2578bd58ccfb.png">
  <br><br>
  
  ### ⚒ 기술 스택
  ![Python](https://img.shields.io/badge/Python-3766AB?style=flat-square&logo=Python&logoColor=FFFFFF) ![Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-sqare&logo=Apache+Spark&logoColor=white) ![Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square&logo=Apache+Airflow&logoColor=FFFFFF)
  
</div>

## 프로젝트 개요 
- 📅 프로젝트 기간: 2022.04.04 - 2022.04.15
<br>

## 프로젝트 목표
- 대용량 데이터에서의 파이프라인을 구축
- TLC 데이터를 이용해 택시요금 예측 ML 모델링 
<br>

## 데이터 파이프라인 
<img src="https://user-images.githubusercontent.com/86868063/169531300-638eab73-da8f-46c6-89ef-8e2672134c7d.png">
<br>

## 프로젝트 과정
- Spark SQL을 이용해 수집한 데이터를 분석 후 전처리 진행 
- Spark MLlib을 이용해 전처리 완료된 데이터로 머신러닝 모델 학습 후 저장 
- Spark를 통해 진행한 작업을 Airflow Task로 구현하여 자동화 
<br>

## 프로젝트 회고
- 프로젝트를 진행함으로써 Spark와 Airflow를 이용해 대용량 데이터를 처리하는 방법을 배워볼 수 있는 계기가 되었다. Spark나 Airflow 둘다 생각보다 어렵지는 않았지만 스트리밍 파이프라인과 연결하는 부분에서 어려움을 겪어 현재는 배치 파이프라인만 완성되었기 때문에 추후에 스트리밍 파이프라인에 대해서도 더 학습해서 배치 파이프라인과 스트리밍 파이프라인을 연결하는 프로젝트를 진행하면 더 좋겠다는 생각이 들었다. 
<br>
