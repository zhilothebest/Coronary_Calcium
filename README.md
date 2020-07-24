# Coronary_Calcium
CAIDM Research

# Dataset Use Statement

Due to the agreement with the creators of the orCA Score dataset (https://orcascore.grand-challenge.org/), the dataset can not be publicly posted, or distributed to anyone outside of this project.
If you have access to this repo, **please do not share this dataset with anyone.**

##### At this time, if you would like access to the dataset, please let me know. It is to big to upload

# Naming Convention of Dataset
**orCA Score Data Set Naming** 

The file names are TR for training, TE for testing, VA for validation. V indicated the vendor number (one of four) and P is indeed the patient number for that vendor. CTAI means CT angiography image, CTI means non-contrast CT image. R means segmentation image.

Please ask if you wish to see orCA Score dataset

** StructSeg 2019 Dataset Naming **

There are 4 zip files corresponding to the 4 tasks of the challenge.

Task1_HaN_OAR.zip: Organ-at-risk segmentation from head & neck CT scans. There are 50 folders and each folder contains a data file (data.nii.gz) and an annotation file (label.nii.gz) of one patient. The 22 annotated OARs contain Brain_Stem,Eye_L,Eye_R,Lens_L,Lens_R,Opt_Nerve_L,Opt_Nerve_R,Opt_Chiasma,Temporal_Lobes_L, Temporal_Lobes_R,Pituitary,Parotid_Gland_L,Parotid_Gland_R,Inner_Ear_L,Inner_Ear_R,Mid_Ear_L,Mid_Ear_R, T_M_Joint_L,T_M_Joint_R,Spinal_Cord,Mandible_L,Mandible_R, corresponding to the label 1 to 22 in the annotation file.
Task2_Naso_GTV.zip: Gross Target Volume segmentation of nasopharynx cancer. Same format as above. The label 1 means GTV of nasopharynx cancer, otherwise background.
Task3_Thoracic_OAR.zip: Organ-at-risk segmentation from chest CT scans. Same format as above. The 6 annotated OARs contain Lung_L,Lung_R,Heart,Esophagus,Trachea,Spinal_Cord, corresponding to the label 1 to 6 in the annotation file.
Task4_Lung_GTV.zip: Gross Target Volume segmentation of lung cancer. Same format as above. The label 1 means GTV of lung cancer, otherwise background.

# Tasks
- [x] Organize Datasets
- [x] Figure out how to load data images into python
- [x] Image Preprocessing//
figured out rotation into axial plane. Have a function for changing color to RGB, but need to think about how to make input shape all equal
- [ ] Create basic NN//
working with TF on error
- [x] Find Heart specific segmentation
- [ ] Create NN for Heart Segmentation
