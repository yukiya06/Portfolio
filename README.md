## 이커머스 (Instacart) 판매 데이터 분석
#### 재주문을 장려하기 위한 마케팅 인사이트 도출 [🔗프로젝트 URL](https://github.com/yukiya06/E-commerce_DataAnalysis)

**[ 인스타카트 소개 ]** 미국 온라인 식료품 구매 서비스 인기 앱, 데이터와 AI활용한 지능화 된 개인 서비스를 제공  
**[ 담당 업무 ]**  프로젝트 설계, 트렌드와 패턴을 식별, 시각화, 대시보드, 연관상품분석, 비지니스 인사이트 도출  
  * 분석 목적: 많은 비용이 소요되는 신규 고객 확보 외에 기존 고객의 재주문 장려하여 매출 증대 목표  
  * 재주문을 장려하기 위한 가설 검증 및 마케팅 인사이트 도출
    - 가설 검증:  **재주문**에는 **패턴**이 있다.
    - **패턴** 정의: **주문 간격, 횟수, 상품 수, 상품 구성, 주문 요일 및 시간**에 특징이 있다.
        - 해당 패턴을 파악하고, **연관 상품 분석**을 통한 상품 추천 시스템을 구성하여 재주문을 장려한다.  

**[ Skill ]** Datastudio, Scikit-learn, Gensim, Pandas  

## 급식 식단 추천 시스템을 위한 음식 메뉴 다중분류모델 개발
#### 새로운 메뉴들을 특징에 따라 라벨링 하는 모델 작업 (누비랩 협업)  [🔗프로젝트 URL](https://github.com/yukiya06/Meal_Planning_Classification)
**[ 누비랩 소개 ]**   Korea AI Startup 100 선정, AI기반의 음식물 데이터 분석 솔루션 제공  
**[ 역할 / 담당 업무 ]**  프로젝트 설계, 데이터 전처리, 시각화, 모델링, 비지도 학습 결과 교차 분석
  * 개발 목적: 신 메뉴들을 분류하여 구분하고, 식단의 음식 재료, 조리법 등이 겹치지 않게 검수 하기 위해 활용 
  * 누비랩 식품 분류 기준에 따라 대분류 (7종류), 중분류 (26종류)로 신메뉴 분류 모델 담당 
    - 기존 라벨링 자료를 모델(KoBERT)에 학습 시키고 결과 검증 → 신규 데이터 분류 후 검증 
    - 신규 데이터는 정답 라벨이 없으므로 분류 후 결과를 다양한 방식으로 여러 번 교차 검증 및 시각화
      * **클러스터링**(K-Means), **키워드 필터링**(KoNLPy Okt), **Word Cloud**

**[ Skill ]** Pandas, Scikit-learn, KoBERT, API활용

## 중고차 판매 가격 예측 API 서비스 개발
#### 데이터 파이프라인 구성 및 다중선형회귀 모델을 통한 가격 예측 서비스 구현  [🔗프로젝트 URL](https://github.com/yukiya06/UsedCar_Values)
**[ 담당 업무 ]**  프로젝트 설계, 데이터 파이프라인 구성, 시각화, 대시보드(Metabase), 모델링,  API 서비스 구현
  * 프로젝트 목적:  데이터와 AI를 활용한 **개인 맞춤 서비스를 제공**, 고관여 제품(가격이 높고, 소비자들의 의사 결정 과정이나 정보 처리 과정이 복잡한 제품)인 자동차 가격을 예측하는 주제로 머신 러닝의 활용 가치를 높임

**[ Skill ]** DB(PostgreSQL), API활용, 스크레이핑, Metabase, Scikit-learn, Flask, Heroku

## 신규 게임 개발 방향 분석
#### 비디오게임 시장 매출 데이터 분석을 통한 다음 분기에 설계 할 게임 제안 [🔗프로젝트 URL](https://github.com/yukiya06/Game_DataAnalysis)
**[ 담당 업무 ]**  프로젝트 설계, 데이터 전처리, EDA, 시각화, 가설 검증, 통계적 검정
  * 분석 목적: 다음 분기 신규 게임 개발을 위한 인사이트 발굴 및 장기적 개발 방향 고찰
  * 가설 검증: 선호 게임에는 **트렌드**가 있다
    - **트렌드** 정의: 장르, 판매 국가, 연도, 게임 플랫폼, 판매 상위 게임에 특징 및 연관성이 있다.
    - 각 항목에 따른 매출 분석 및 시각화, 데이터간 상관관계를 통계적으로 검정하고 개발 방향을 정한다.

**[ Skill ]** Pandas, Scipy
