This repository collects medical data that can be freely accessed and used in research.

## ICU
- **MIMIC-IV** (40k)
	- MIMIC (Medical Information Mart for Intensive Care) is a large, freely-available database comprising de-identified health-related data from patients who were admitted to the **critical care units** of the Beth Israel Deaconess Medical Center. MIMIC-IV contains data from 2008 - 2019.
	- Intro：
		- [MIMIC](https://mimic.mit.edu/)
	- Data:
		- [MIMIC-IV v2.2](https://www.physionet.org/content/mimiciv/2.2/)
	- Code:
		- [GitHub - MIT-LCP/mimic-code](https://github.com/MIT-LCP/mimic-code)
- **eICU** (200k)
	- The eICU Collaborative Research Database is populated with data from a combination of many critical care units throughout the continental United States. The data in the collaborative database covers patients who were admitted to critical care units in 2014 and 2015.
	- intro:
		- [eICU](https://eicu-crd.mit.edu/gettingstarted/overview/)
	- Data:
		- [eICU Collaborative Research Database v2.0](https://physionet.org/content/eicu-crd/2.0/)
	- Code:
		- [GitHub - MIT-LCP/eicu-code: Code and website related to the eICU Collaborative Research Database](https://github.com/MIT-LCP/eicu-code)
- **HiRID - high time resolution ICU data set** (33k)
	- The dataset contains de-identified demographic information and a total of 712 routinely collected physiological variables, diagnostic test results and treatment parameters from more than 33 thousand admissions during the period from January 2008 to June 2016. Data is stored with a uniquely high time resolution of one entry every two minutes.
	- Intro：
		- [HiRID - high time resolution ICU data set](https://hirid.intensivecare.ai/)
	- Data:
		- [HiRID, a high time-resolution ICU dataset v1.1.1](https://www.physionet.org/content/hirid/1.1.1/)
	- Code:
		- [circEWS/preprocessing at master · ratschlab/circEWS · GitHub](https://github.com/ratschlab/circEWS/tree/master/preprocessing)
		- [GitHub - ratschlab/HIRID-ICU-Benchmark: Repository for the HiRID ICU Benchmark (HiB) project](https://github.com/ratschlab/HIRID-ICU-Benchmark)
- **AmsterdamUMCdb** (23k)
	- This is the first freely accessible intensive care database from within the European Union. It contains de-identified health data related to tens of thousands of intensive care unit admissions, including demographics, vital signs, laboratory tests and medications.This version (v1.0.2)contains data related to 23,106 intensive care unit and high dependency unit admissions of adult patients from 2003-2016.
	- Intro & Data:
		- [AmsterdamUMCdb - Amsterdam Medical Data Science](https://amsterdammedicaldatascience.nl/amsterdamumcdb/)
	- Code:
		- [GitHub - AmsterdamUMC/AmsterdamUMCdb](https://github.com/AmsterdamUMC/AmsterdamUMCdb)
- **Critical care database comprising patients with infection at Zigong Fourth People's Hospital** (2.79k)
	- a critical care database relating to patients with infection from Chinese hospital 
	- [Critical care database comprising patients with infection at Zigong Fourth People's Hospital v1.1](https://physionet.org/content/icu-infection-zigong-fourth/1.1/)

## Operation Room
- **VitalDB**
	- The VitalDB (Vital Signs DataBase) is an open dataset created specifically to facilitate machine learning studies related to monitoring vital signs in surgical patients. This dataset contains high-resolution multi-parameter data from 6,388 cases, including 486,451 waveform and numeric data tracks of 196 intraoperative monitoring parameters, 73 perioperative clinical parameters, and 34 time-series laboratory result parameters.
	- Intro:
		- [VitalDB](https://vitaldb.net)
	- Data:
		- [VitalDB, a high-fidelity multi-parameter vital signs database in surgical patients v1.0.0](https://www.physionet.org/content/vitaldb/1.0.0/)
	- Code:
		- [Dataset : VitalDB](https://vitaldb.net/dataset/?query=lib)

##  Specialized disease
- **Alzheimer’s Disease** Neuroimaging Initiative (ADNI) database 
	- provides imaging, clinical, and genetic data for over 2220 patients spanning four studies
	- Intro & Data：
		- [ADNI | Alzheimer's Disease Neuroimaging Initiative](https://adni.loni.usc.edu/)
- **SEER**
	- The Surveillance, Epidemiology, and End Results (SEER) Program provides information on **cancer statistics** in an effort to reduce the cancer burden among the U.S. population.
		- [Surveillance, Epidemiology, and End Results Program](https://seer.cancer.gov/)
- **Sleep Heart Health Study (SHHS)**
	- Using the Compumedics PS polysomnograph, sleep studies were obtained in an unattended setting, usually in the homes of the participants, the dataset include ECGs, EEG  and so on.
	- Intro & Data:
		- [BioLINCC: Sleep Heart Health Study (SHHS)](https://biolincc.nhlbi.nih.gov/studies/shhs/)
- **Hospitalized patients with heart failure**
	- a retrospective heart failure dataset using electronic health data collected from patients who were admitted to a hospital in China
	- Intro & Data:
		- [Hospitalized patients with heart failure: integrating electronic healthcare records and external outcome data](https://physionet.org/content/heart-failure-zigong/)

## Medical notes
- **medal**: Large medical text dataset curated for **abbreviation disambiguation**, designed for natural language understanding pre-training in the medical domain
	- [GitHub - McGill-NLP/medal: Large medical text dataset curated for abbreviation disambiguation, designed for natural language understanding pre-training in the medical domain](https://github.com/McGill-NLP/medal)
- **MedQA**: A large-scale Open domain **question answering** dataset from medical exams
	- [GitHub - jind11/MedQA: Code and data for MedQA](https://github.com/jind11/MedQA)
- **PubMedQA**: A Dataset for Biomedical Research **Question Answering**
	- [PubMedQA Homepage](https://pubmedqa.github.io/)
- **MedMCQA**: A large-scale (194k), **Multiple-Choice Question Answering** (MCQA) dataset designed to address real world medical entrance exam questions.
	- [GitHub - medmcqa/medmcqa: A large-scale (194k), Multiple-Choice Question Answering (MCQA) dataset designed to address realworld medical entrance exam questions.](https://github.com/medmcqa/medmcqa)
- **MMLU**:Measuring Massive Multitask Language Understanding, These include **practice questions** for tests such as the Graduate Record Examination and the United States Medical Licensing Examination.
	- [GitHub - hendrycks/test: Measuring Massive Multitask Language Understanding | ICLR 2021](https://github.com/hendrycks/test)

## Medical images
[GitHub - ys-zong/MEDFAIR: MEDFAIR: Benchmarking Fairness for Medical Imaging](https://github.com/ys-zong/MEDFAIR)
- CheXpert
- REPECT
- RadFusion
- MIMIC-CXR

## Search
- You can search medical or other datasets in nature `scientific data` journal
	- [medical data | Nature Search Results](https://www.nature.com/search?journal=sdata&q=medical%20data)
- `PhysioNet` website
	- [PhysioNet](https://www.physionet.org/)
- `Google dataset`
	- [Dataset Search](https://datasetsearch.research.google.com/)