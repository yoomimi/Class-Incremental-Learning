# 🚩 Class-Incremental Learning
<br>

### ✨ What is CIL? & Why CIL?
<br>
Class-Incremental Learning (CIL)은 모델이 시간이 지남에 따라 점진적으로 새로운 클래스를 학습하는 학습법입니다.
전통적인 학습 방식에서는 모든 클래스를 한 번에 학습하지만, CIL에서는 데이터가 점진적으로 제공되며 모델이 새로운 클래스를 학습할 때 이전에 학습한 내용을 잊지 않도록 하는 것이 중요합니다.
이는 CIL이 다루는 Catastrophic Forgetting 문제라고도 불립니다.
<br>
<br>
모든 데이터를 한 번에 저장하고 학습하는 것은 비효율적이고 어쩌면 비현실적일 수 있습니다.
특히, 데이터가 매우 크거나 민감한 정보를 포함하는 경우에는 CIL을 이용한 점진적인 학습이 필수적입니다.
