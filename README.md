# Data_Project-Call_Center_Patent_Analysis_2021
## Analysis
> 1. USPTO PATENT 통합 전처리.ipynb
* 기존 Blockchain 특허 분서때의 API 점검으로 전체 데이터를 사용함
* 파일이 크기 때문에 다음 사이트에서 tsv들을 다운을 받고 실행하길 바람
* cpc_current.tsv, patent.tsv
* 이 파일들을 통해 dataset.csv를 코드를 통해 생성 가능함

> 2. USPTO 검색.ipynb
* dataset.csv를 통해 원하는 특허 분석을 통해 수집 가능함

> 3. CPC 분석.ipynb
* CPC 상위 및 하위 분석
* CPC co-occurrence

> 4. 상관관계.ipynb
* Modularity별 Source 및 Target으로 인한 상관관계

> 5. CPC 비율 분석.ipynb
* CPC Counter별
* CPC OrderedDict

> 6. Call Center Keyword Matrix.ipynb
* Abstract을 이용한 keyword 전처리 수행 (lower, regular expression, stopwords, lemmatizer, NN)
* Keyword co-occurrence

## Data Source
* https://patentsview.org/download/data-download-tables
