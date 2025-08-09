
---

# Project 972 – 데이터 분석 포트폴리오

본 저장소는 972시간 동안 진행한 5개의 데이터 분석 프로젝트를 모아둔 포트폴리오입니다.
각 프로젝트는 실제 데이터를 활용하여 문제 정의부터 데이터 처리, 모델링, 시각화, 결과 보고까지 전 과정을 경험하며 완성했습니다.
README와 함께 각 프로젝트 폴더로 이동하시면 기획서, 발표자료, 분석 코드, 결과 보고서를 확인하실 수 있습니다.

---

## 프로젝트 목록

### 1. [통계학 기반 금융 데이터 분석](./project-statistics)

**목표:** IT 아웃소싱 플랫폼의 거래 데이터를 바탕으로 수수료 구조, 거래 성사율, 전문가 특성 등을 분석하여 개선 전략 제안
**주요 성과:**

* 4개 데이터 병합 및 이상치/결측치 처리 규칙 수립
* 다중 회귀·로지스틱 회귀 분석으로 거래 성사 영향 요인 도출
* 가격 정책·전문가 인센티브·수수료 구조 개선안 제시

**기획서:** [statistics\_project\_proposal.pdf](./project-statistics/results/statistics_project_proposal.pdf)
**발표자료:** [statistics\_project\_presentation.pdf](./project-statistics/results/statistics_project_presentation.pdf)

---

### 2. [머신러닝 기반 신용카드 고객 세그먼트 분류](./project-ml)

**목표:** 카드 사용 데이터를 기반으로 고객을 A\~E 세그먼트로 분류하여 맞춤 마케팅 전략 수립
**주요 성과:**

* 내부·외부 데이터 병합 및 스키마 차이 해결
* 인코딩·스케일링·중복 제거 규칙 표준화
* XGBoost, LightGBM, CatBoost 비교 → Soft Voting 앙상블 모델 최종 선정

**기획서:** [ml\_project\_proposal.pdf](./project-ml/results/ml_project_proposal.pdf)
**발표자료:** [ml\_project\_presentation.pdf](./project-ml/results/ml_project_presentation.pdf)

---

### 3. [지하철 혼잡도 예측 기반 광고 전략 최적화](./project-dl)

**목표:** 서울 지하철 혼잡도를 시간·노선·기상 정보로 예측하고 광고 전략 최적화에 활용
**주요 성과:**

* 3년치 혼잡도·기상·환경 데이터 통합
* LSTM 기반 예측 모델 개발 (노선별 RMSE 3.14\~4.93)
* 혼잡도 패턴 분석 기반 광고 집행 전략 제안

**기획서:** [dl\_project\_proposal.pdf](./project-dl/results/dl_project_proposal.pdf)
**발표자료:** [dl\_project\_presentation.pdf](./project-dl/results/dl_project_presentation.pdf)

---

### 4. [정형 데이터 기반 AutoML 분석 및 고객 인사이트 도출](./project-mldl)

**목표:** 고객 세분화, 이탈 예측, 배송일 예측 등 운영 개선을 위한 데이터 분석
**주요 성과:**

* RFM 분석 기반 고객 세그먼트별 마케팅 전략 제안
* AutoML 기반 이탈 예측 모델 구축 및 리텐션 전략 수립
* 배송 지연 사전 감지 모델 개발

**기획서:** [mldl\_project\_proposal.pdf](./project-mldl/results/mldl_project_proposal.pdf)
**발표자료:** [mldl\_project\_presentation.pdf](./project-mldl/results/mldl_project_presentation.pdf)

---

### 5. [iM 환율적 참견시점 (Project FX-Risk)](./project-fxrisk)

**목표:** 환율 예측과 맞춤형 헤지 전략 제안을 통한 환리스크 대응 플랫폼 구축
**주요 성과:**

* USD, CNY, JPY, EUR 환율 예측 (LSTM R² 최대 0.9555)
* EPU 지수·뉴스 토픽 모델링 기반 변동성 해석 기능 구현
* 예측 + 손익 시뮬레이션 + 전략 제안까지 원스톱 서비스 설계

**기획서:** [fxrisk\_project\_proposal.pdf](./project-fxrisk/results/fxrisk_project_proposal.pdf)
**발표자료:** [fxrisk\_project\_presentation.pdf](./project-fxrisk/results/fxrisk_project_presentation.pdf)
**보고서:** [fxrisk\_project\_report.pdf](./project-fxrisk/results/fxrisk_project_report.pdf)

---

## 폴더 구조

```
project972/
├── project-statistics/   # 금융 데이터 통계 분석
├── project-ml/           # 신용카드 고객 세그먼트 분류
├── project-dl/           # 지하철 혼잡도 예측
├── project-mldl/         # AutoML 기반 고객 분석
├── project-fxrisk/       # 환율 예측 & 전략 제안
└── README.md             # 현재 파일
```

---

## 특징

* 모든 프로젝트는 **기획서·발표자료·분석 코드**를 포함
* 데이터 전처리부터 모델링·시각화·보고서 작성까지 **E2E(End-to-End)** 수행
* 재현 가능한 코드와 문서화로 **팀 협업 및 유지보수 용이성 확보**

---
