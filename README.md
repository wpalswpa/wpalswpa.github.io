# STT + LLM 우울 위험 스크리닝

복지상담 음성 데이터를 Whisper로 전사하고, GPT Zero-shot 분류기로
우울·비우울을 분류한 연구 프로젝트입니다.

## 주요 결과
| 모델 | Accuracy | Precision | Recall | F1 |
|------|----------|-----------|--------|----|
| GPT-3.5 turbo | 0.57 | 0.70 | 0.25 | 0.37 |
| GPT-4o | 0.57 | **0.82** | 0.19 | 0.31 |

## 사용 기술
- OpenAI Whisper (STT 전처리)
- GPT API + Scikit-LLM (Zero-shot 분류)
- Python, Google Colab

## 데이터
AI Hub 정신건강 상담 데이터 5,000건 (우울/비우울 각 2,500건)
