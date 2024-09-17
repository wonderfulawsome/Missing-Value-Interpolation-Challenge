# Missing-Value-Interpolation-Challenge

## Dataset Info

### 1. data.csv [파일]
- **시나리오**: SAMPLE_00000 ~ SAMPLE_62628은 일정한 텀마다 센서에서 온도를 측정한 데이터이며, 이 과정에서 기기/통신 결함으로 인한 결측이 발생함.
- **Columns**:
  - `id`: 샘플 고유 ID
  - `Value`: 일정한 텀마다 센서에서 측정된 온도 값 (°C)

### 2. sample_submission.csv [파일] - 제출 양식
- **Columns**:
  - `id`: 샘플 고유 ID
  - `Value`: 결측치를 모두 보간한 온도 값 (°C)

## Notebooks Overview

### 1. EDA.ipynb
- **목적**: 결측치가 있는 데이터를 탐색하고, 데이터 분포와 결측치 패턴을 분석하는 노트북.
- **주요 내용**:
  - 결측치 분석
  - 기술 통계
  - 데이터 시각화

### 2. KNNImputer.ipynb
- **목적**: K-최근접 이웃(K-Nearest Neighbors) 방법을 이용하여 결측치를 보간하는 노트북.
- **주요 내용**:
  - KNN 알고리즘으로 결측치 보간
  - 보간 후 결과 시각화

### 3. LSTM.ipynb
- **목적**: 시계열 예측 모델인 LSTM(Long Short-Term Memory)을 사용하여 결측치를 보간하는 노트북.
- **주요 내용**:
  - 시계열 데이터 전처리
  - LSTM 모델 학습 및 평가

### 4. LinearRegression.ipynb
- **목적**: 선형 회귀를 사용하여 결측치를 보간하는 노트북.
- **주요 내용**:
  - 선형 회귀 모델로 결측치 예측
  - 모델 성능 평가

### 5. SVR.ipynb
- **목적**: 서포트 벡터 회귀(SVR)를 사용하여 결측치를 보간하는 노트북.
- **주요 내용**:
  - SVR 모델로 결측치 보간
  - 성능 평가 및 시각화

### 6. TPOTRegressor.ipynb
- **목적**: TPOT(Tool for Optimizing Pipelines)를 사용하여 자동화된 회귀 모델을 찾고 결측치를 보간하는 노트북.
- **주요 내용**:
  - TPOT으로 최적 모델 탐색
  - 보간 결과 평가

### 7. cubic.ipynb
- **목적**: 3차 보간법(Cubic Interpolation)을 이용하여 결측치를 보간하는 노트북.
- **주요 내용**:
  - 3차 보간법 적용
  - 결과 시각화

### 8. index.ipynb
- **목적**: 다른 노트북 파일에 대한 인덱스 및 개요 제공.

### 9. linear interpolation.ipynb
- **목적**: 선형 보간법을 사용하여 결측치를 보간하는 노트북.
- **주요 내용**:
  - 선형 보간법 적용
  - 결과 시각화 및 평가

### 10. mice.ipynb
- **목적**: MICE(Multiple Imputation by Chained Equations) 알고리즘을 사용하여 결측치를 보간하는 노트북.
- **주요 내용**:
  - MICE 알고리즘 설명 및 적용
  - 결과 평가 및 시각화

### 11. spline.ipynb
- **목적**: 스플라인 보간법(Spline Interpolation)을 이용하여 결측치를 보간하는 노트북.
- **주요 내용**:
  - 스플라인 보간법 적용
  - 결과 시각화 및 성능 평가

### 12. 다항식 보간.ipynb
- **목적**: 다항식 보간법을 사용하여 결측치를 보간하는 노트북.
- **주요 내용**:
  - 다항식 보간법 적용
  - 결과 시각화 및 성능 평가

