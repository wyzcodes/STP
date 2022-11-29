* Intro 
	* The growth of AI, AI ARMS Race 
	* Develop and deploy lethal autonomous weapons systems, especially on unmanned systems, robots and unmanned air vehicle(UAV). 
AI 기술은 복잡한 정보를 처리하기 용이하며 멀티모달로 들어오는 정보를 수집하고,수집된 정보 기반으로 알고리즘을 학습시켜 새로운 정보를 처리하기에 용이하기 때문에 많은 산업 분야에서 큰 관심을 갖고 개발하고 있다. 특히 국방 분야에서 무인화된 무기 체계의 개발에 큰 역할을 할 수 있기 때문에 AI에 관심을 갖고 있다. Target identification and Autonomous response.
AI is no longer treated as R&D project. The scope of deployment has enlarged especially in military field, for example Reconaissance, Automation, Decision making 등 다양한 분야에 사용하기 위한 목표로 개발하고 있다.  
AI has potential to improve efficiency and accuracy. widespread adoption raise concerns about shifting decision-making away from humans. To increase trust between the department and the many actors involved with AI programs. 

Develop artificial intelligence technologies to be applied military weapons, joining the global competition to develop autonomous arms. 

Responsible artificial intelligence. People mistakenly assume that by incorporating AI into programs, humans play a lesser role. In reality, human factors become more important in decision-making when using the technology. The members of the military can trust the technologies that they're given. 
Test and evaluation processes developing for internal use, they'll be able to advocate for and socialize and normalize among other militaries around the world. 


Reduces human labor, improves sensing, enhance cyber security, facilitates logistics 
High cost of implementation, cannot replace human yet, doesnot improve with experience


Non-deterministic, non-linear, high-dimnesional, probabilistic, and continuously learning. Traditional validation techniques are insufficient. 
The race between the world's superpowers to outpace each other has also made people uneasy as countries might not play by the norms and consider ethics while designing weapons systema, leading to disastrous implications on the battlefield. 
https://analyticsindiamag.com/the-ethical-challenges-of-ai-in-defence/

AI Blackbox and the resulting lack of explainability would open it up for risk in its application in highly regulated or critical environments. 
Attack on Training machine learning. Designated dataset, trained on errors to give false results. 

Operational risks from the reliability, fragility, and security of AI systems. 




# Responsible AI 
In 2018, after learning about their company's involvement in Project Maven, a military effort to develop AI to analyze surveillance videos, thousands of Google employees protested. The protests ended with around a dozen employee resignations. Google did not renew the contract in 2019. 
In 2020, the Pentagon published a document outlining its core values for AI. Under the principles, the Pentagon seeks to make AI responsible, equitable, traceable, reliable and governable in combat and non-combat situations. 

Maven: 구글이 미국 기업이지만 미국만의 이익이 아닌 세계의 발전에기여할 수 있는 서비스를 해야 한다는 의견이 있었음. 펜타곤과 진행하는 프로젝트는 구글이 공개한 오픈소스 S/W를 사용하기 때문에 프로젝트에 참여하지 않더라도국방부는 여전히 이 기술을 사용할 수 있었음. 
Pentagon contract dubbed Project Maven that used te company's artficial inteligence technology to aalyze dronesurveillance footage. 
Gougle wouldn't renew the contract and announced guidng prnciples for future AIprojects that forbid work on weapons and survillance projects volatng internationally accepted norms. 

Requirements
Responsible AI governance, warfighter trust, AI productand acquisition lifecycle, requirements validation, ersponsible AI ecosystem and AI workforce.

* Risk 
	* Consolidation of power and technological advantage in the hands of one group, if one group achieves superior AI technology, it is only reasonable to conclude that AI-enabled capabilities could be used to threaten our critical infrasturcture, amplify disinformation campaign, and wage war. 
* Economic dominance and Soft- power 

Value laden decisions
- Potential geopolitical implication 
	* no race terminology surrounding the race is dangerous. The ehetoric aruond the AI race and the impotance of being first does not encourage te type of thuoghtful deliberation with stakeholders required to produce AI technology that is temost broadly beneficial to society and could self-fullingly induce a race. 
	* Emerge strong incentives to cut corners on safetyconsiderations, such as bias and fairness. 

* Industry funded science. 
	* In this case, The funding source is the government. The groupd of governments or associations of academia should take roles of ethics and philosophy. 

# Epistemic uncertainty on AI technology itself
* Epistemic uncertainty
* The model is only able to identify the trained samples. They figures probability distribution for test datasets, to assign probability of categories. 
* When the samples passes the classifier, if the probability of the images are calculated, to determine which categories has higher probability. (slightly higher) 
	* The confident of the result
	* Prediction is uncertain
	* Measures of uncertainty of the model, return one of the three classes. Calculate the entropy. total uncertainty is composed of two different type of uncertainty.  : 
# Uncertainty
* Total uncertainty = data uncertainty + model uncertainty 
* Model uncertainty = Epistemic uncertainty, knowledge uncertainty
* Data uncertainty : Aleatory uncertainty 
	* The sum of probability distribution is equal to 1. 
* Input images 

Aleatory uncertainty: 데이터에 포함된 고유 노이즈로 발생하는 불확실성. 센서 등에서 데이터를 취득할 때 그 데이터가깨끗하다고 무조건 단정지을 수 없듯이 측정 단계부터포함된 데이터 고유 노이즈로인한 것으로 데이터를 많이 취득한다고해서 없어지지 않음. 입력데이터의종류마다 노이즈가 일정하다고 가정한 homoscedastic uncertainty와 입력마다 노이즈가 서로 다른 heteroscedastic uncertainty로 나눌 수 있다. practical 한 상황에서는 heteroscedastic uncertainty를 모델링하는 것이 중요. 

epistemic uncertainty는 모델 파라미터의 uncertainty이다. 모델이 결과를 얼마나 확신할 수 있느냐. 데이터가 충분할 수록 줄일 수 있다. 

# Inductive risk
A term first used by Hempel, 1965, is the chance that one will be wrong in accepting or rejecting a scientific hypothesis. 
Risk of inductive error meant that values must play a role in science. 
values could act as presuppositions for scientific arguments. 
all logical relevance to the proposed hypothesis since they can contribute neither to its support nor to its disconfirmation. 

Inductive risk: decisions on How much evidence is enough to sufficient to confirm or refute hypotheses require non-epistemic values. No strict epistemic standard for how much evidence is enough to accept a theory, and the decision depends on the risks involved. 
Require more evidence before decidign.

Distinction between epistemic and non-epistemic values. Traditional epistemic values are somteimes just manifestation of non-epsitemic values. 


Inductive bias
모델이 갖는 일반화의 오류 Generalization problem은 불안정하다는 것(brittle)과 겉으로만 그럴싸해보이는것 Spurious가 있다. 모델이 주어진 데이터에 대해 잘 일반화한 것인지, 혹은 주어진 데이터에만 잘 맞게 된 것인지 모르기 때문에 발생하는 문제. 이러한 문제를 해결하기 이ㅜ한 것이 Inductive bias. 주어지지 않은 입력의 출력을 예측하는 것. 일반화의 성능을 높이기 위해 만약의 상황에 대한 추가적인 가정 Additional Assumption을 추가함. 

Models are brittle: 아무리같은 의미의데이터라도 조금만 바꾸면 모델이 망가짐
Models are Spurious: 데이터의 진정한 의미를 파악하지 못하고 결과(Artifaacts)와 편향 Bias를 암기한다. 

성공적으로 학습하여 일반화가 잘 된 모델은 Inductive bais유형을 갖게 되는데, 보지 못한 데이터에 대해서도 귀납적 추론이 가능하도록 하는 알고리즘이 가지고 있는 가정의 집합. 

* To ensure meaningful human control. 
* Not to develop autonomous weapons and ensure meaningful human control. 
* effective bans on previous arms technologies and urged ban any work on lethal autonomous weapons, and to refrain from AI uses taht wuold harm human lives. 

AI is used to create machines able to perceive the environment and make decisions. 
Decision made by robots -> Machines are taking position of 보조 subsidiary decision maker to help commanders. 
Potential 

# Intellectual property: AI's Role in Modernizing 

![[Pasted image 20221107142535.png]]
Ref) https://www.army-technology.com/analysis/artificial-intelligence-innovation-among-military-industry-companies-has-dropped-off-in-the-last-year/ 

# Pros: Truthworthy
* Military standards
Military standards are one of the most highly reliable qualification system. 
Staff trainiing is an essential component to further refinement of the process. Training capability with certified. 
Military workmanshoip standards compliance. 

Reference: https://www.dsp.dla.mil/Specs-Standards/ 
Standardization documents are developed and used for products, materials, and processes that have multiple applications to promote commonality and interoperability among the Military Departments and the Defense Agencies and between the Unitesd states and its allies. 
To limit the variety of items in the military supply system. 

The acquisition streamlining and standardization information system (ASSIST) database identifies approved deffense tand federal stadndardization documents, adopted non-government standards(NGS), and US ratified material international standardization agreements. 

# Compromise: UN ODA Office for Disarmament Affairs(August 2019)

UN advocated against the deployment of technologies in the field, however it is unlikely that a complete ban can be enforced. The best way forward is to define a set of broad guidelines for its deplloyment to secure the world. 
AI alone shouild never be allowed to make judgement calls in matter of arms. There sould be human surveillance of its decisions before they are executed int he field. 
Persons entrusted with deploying AI must have a thorough knowledge of this tech. 
Human should have sufficient oversight and the ability to disengage a malfunctioning system immediately. 


https://www.un.org/disarmament/the-militarization-of-artificial-intelligence/ 

Starting point for more robust dialogues among diverse communities of stakeholders as they endeavor to maximize the benefit of AI while mitigating the misapplication of this important technology. 

* Potential risks of military applications of AI : undoubtedly are risks posed by applications of AI within the military domain. 
	* Lethal autonomous weapon systems (LAWS) 
* Potential benefits of Military application of AI: develop state-level and multilateral means of capturing these benefits safely 


Reference
Dual-Use and Truthworthy? A mixed methods analysis of AI diffusion between Civilian and Defense R&D 
https://link-springer-com.libra.kaist.ac.kr/article/10.1007/s11948-022-00364-7