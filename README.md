강화 학습 기반 공유 자전거 최적 분배 방안 연구  
(A Study on the Optimal Distribution of Shared Bikes Based on Reinforcement Learning)
===========================================================================================

서울시 공유 자전거 "따릉이"의 배치 및 구조를 토대로 가상의 환경을 만들어 강화학습(Actor-Critic, DQN)을 활용한 성능을 테스트한다. 간단한 Heuristic-Rule 기반 행동에 비해 어떤 성능을 보이는지 테스트하고 더 나아가 공유 퍼스널리티 구조에 어떻게 적용될 수 있을지 살펴보자. 

[[논문]강화 학습 기반 공유 자전거 최적 분배 방안 연구.pdf](https://github.com/yjch00/RL/files/11119153/default.pdf)  
[[발표]강화 학습 기반 공유 자전거 최적 분배 방안 연구.pdf](https://github.com/yjch00/RL/files/11119154/default.pdf)

## Abstract

본 연구에서는 강화학습 기반의 최적 분배를 위한 서울시 공유자전거 불균형 문제에 대해 마르코프 결정 과정 모델을 제안한다. 제안된 마르코프 결정 과정 모델에서 에이전트에 입력되는 상태는 각 대여소의 자전거 수, 트럭 보유 자전거 수, 대여소 인덱스를 기준으로 한 트럭의 현재 위치이다. 에이전트의 행동은 두 가지 목적 함수를 최소화하도록 정의하였는데 첫 번째는 대여 수요 발생 시 대여를 못한 고객을 최소화하는 것이고 두 번째는 특정 대여소에 일정 숫자 이상의 자전거가 쌓이는 경우를 최소화하는 것이다. 
 최종적으로 정의된 마르코프 결정 과정 모델을 기반으로 Actor-Critic 강화학습 알고리즘을 적용하여 현실의 문제를 단순화하여 새로운 문제를 만들었다. 문제에 대해 최적 분배 방안을 수립하는 에이전트를 학습하였고 5가지 실험을 진행하며 해당 에이전트가 휴리스틱 규칙에 비해 어떠한 성능을 보이는지 평가하였다. 결정론적 문제에서는 휴리스틱 규칙이 더 좋은 성능을 보였지만 확률론적 문제에서 정규분포의 표준편차를 이용해 대여와 반납의 변동성을 키울수록 에이전트의 성능이 좋아짐을 확인할 수 있었다. 실제 문제의 경우 실험에서 설정한 변동성보다 더욱 변동성이 크고 완전한 무작위성이 존재하므로 에이전트가 현실 문제에 대해 휴리스틱 규칙보다 더욱 효과적인 분배 전략을 세울 수 있다는 점을 확인할 수 있었다. 이를 통해 본 연구에서 제안한 최적 분배 방안에 대한 마르코프 결정 과정 모델의 효과성과 강화학습의 적용을 통한 서울시 공유자전거 따릉이 분배 계획 자동화의 가능성을 확인한다.

주요어 : 강화학습, 공유자전거, 따릉이, 공유퍼스널리티
