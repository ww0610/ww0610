![banner](https://capsule-render.vercel.app/api?type=waving&color=0047AB&height=300&section=header&text=Hello%20World%20and%20Goodbye%20Cruel%20Bugs%20%F0%9F%8C%87&fontSize=40&fontColor=ffffff)

Hello! I'm on a journey to become a Cloud Data Engineer, with a focus on scalable, cloud-native data solutions.  
こんにちは！クラウドネイティブなデータソリューションに取り組み、クラウドデータエンジニアを目指しています。


## Tech Stack

<img src="https://img.shields.io/badge/Azure-0078D4?style=flat&logo=Microsoft-Azure&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=Amazon-AWS&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=Microsoft-SQL-Server&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white"/>
<img src="https://img.shields.io/badge/DBeaver-372923?style=flat&logoColor=white&label=DBeaver"/>
<img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=PowerShell&logoColor=white"/>
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white"/>
<img src="https://img.shields.io/badge/Copilot%20Studio-000000?style=flat&logo=githubcopilot&logoColor=white"/>

## Featured Projects

### 🔷 Azure + Copilot Studio
- **Copilot Plugin Integration**  
  Azure SQL Database와 연동되는 Copilot Studio 플러그인을 직접 개발했습니다.  
  플러그인 매니페스트 구성부터 Azure Functions로 API 구성까지 처음부터 직접 다뤄보며 Copilot 아키텍처를 체감했습니다.  
  → Developed a custom Copilot Studio plugin integrated with Azure SQL Database.  
  → Handled everything from manifest authoring to Azure Function deployment and felt the full architecture in action.

- **API 연동 + JSON 응답 처리**  
  Azure Functions에서 외부 API처럼 JSON 응답을 반환하도록 구성하고, Copilot에서 이를 호출해 답변하도록 만들었습니다.  
  단순한 챗봇이 아닌, **실시간 데이터에 기반한 응답 설계**에 집중했습니다.  
  → Configured Azure Functions to behave as an external JSON API endpoint for Copilot queries.  
  → Focused on designing a dynamic, data-driven conversational response.

- **오류 대응 및 테스트 반복**  
  인증 실패, 포맷 오류 등 다양한 이슈를 겪으며 로그 추적과 반복 테스트의 중요성을 체감했습니다.  
  → Faced issues like auth errors and malformed responses; learned through debugging and iterative testing.

- **Azure 리소스 통합 경험**  
  API Management, Application Insights 등 다양한 Azure 서비스와 연계해보며 Copilot 프로젝트 외에도 **리소스 간 연동 구조**를 실습했습니다.  
  → Gained experience integrating multiple Azure services including API Management and Application Insights.  
  → This gave me a broader view of how Azure components work together in a real solution.

---

### 🔷 Azure ML + Designer
- **GUI 기반 ML 경험**  
  Python 없이도 가능한 ML 툴이 궁금해 Azure ML Designer를 사용해봤습니다.  
  분류 모델을 구성하고 실험 파이프라인을 직접 조립해보는 과정을 통해 ML 서비스 흐름을 이해하게 되었습니다.  
  → Used Azure ML Designer to build classification models without writing code.  
  → Assembled the entire pipeline visually and understood the typical ML flow.

- **모델 평가 & 비교**  
  정확도 비교를 위한 모델 여러 개를 만들어 평가한 뒤, **가장 적합한 모델을 골라 엔드포인트로 배포**까지 해봤습니다.  
  → Compared multiple models for accuracy and deployed the best one as a REST endpoint.

---

### 🔷 SharePoint + PowerShell 자동화
- **전체 사이트 대상 정보 보호 자동 수집**  
  조직 내 SharePoint 문서 중 '사내비' 감도 라벨이 붙은 파일만 찾아내는 자동화 스크립트를 작성했습니다.  
  모든 사이트를 반복하며 결과를 CSV로 정리할 수 있도록 했습니다.  
  → Wrote a PowerShell script to scan all SharePoint sites and collect documents labeled as "Internal".  
  → Exported the results into CSV format for reporting.

- **PnP PowerShell & 앱 등록 인증 실습**  
  최신 PowerShell 7 환경에서 PnP PowerShell 모듈을 사용하고, 앱 등록 기반 인증 방식도 처음으로 적용해봤습니다.  
  권한 구성과 REST 호출 구조에 대한 감이 생겼습니다.  
  → Practiced app-based authentication using PnP PowerShell in PowerShell 7.  
  → Understood permission models and REST API patterns.

---

### 🔷 Microsoft 365 보안 & 업데이트 정책 정리
- **Copilot 도입 전 보안정책 구성 지원**  
  고객사의 Copilot 도입에 앞서, 조건부 액세스, DLP, 정보 보호 라벨 등 **필수 정책들을 사전 검토 및 안내**했습니다.  
  → Reviewed Conditional Access, DLP, and AIP policies to support Copilot deployment in enterprise environments.

- **일부 사용자만 최신 채널 배포 구성**  
  Office Deployment Tool(ODT)와 Intune을 조합해 **관리자만 최신 버전을 받게 하는 배포 전략**을 실제로 테스트하고 정리했습니다.  
  → Designed a selective Office update rollout using ODT and Intune, where only admins receive the Current Channel.

- **현장 대응 기반 구성**  
  실제 사용자 환경에서 발생한 문제들을 기반으로 보안 정책 설정 및 변경 제안을 진행한 경험이 있습니다.  
  → Adjusted security settings based on real-world user feedback and troubleshooting cases.

## Blog

I document my learning and projects on Tistory, focusing on cloud-based data engineering and system architecture.

→ 클라우드 기반 데이터 엔지니어링과 시스템 아키텍처 관련 실습을 블로그에 기록하고 있습니다.

Tistory Blog: [Cloud Data Engineer 여정](https://ww0610.tistory.com/)

###  Featured Series
- [Azure ML 시리즈]  
  Azure Machine Learning 실습 (Designer, 모델 배포, AI Search 연동 등)

- [3-Tier Architecture 구축기]  
  AD + IIS + SQL Server로 구성한 전통적 아키텍처 구성 실습

- [PowerShell + SharePoint 자동화]  
  조직 전체 SharePoint 문서 대상 감도라벨 추출 스크립트 개발기

- [Copilot Studio 실습기]  
  Azure SQL과 연동된 Copilot 플러그인 개발 및 API 연동 흐름 정리


## GitHub Stats

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=ww0610&show_icons=true&theme=tokyonight)](https://github.com/ww0610)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ww0610&layout=compact&theme=tokyonight)](https://github.com/ww0610)




