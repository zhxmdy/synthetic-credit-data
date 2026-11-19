# Synthetic Data Generation: Methods, Tools, and Resources

A collection of implementation repositories, supporting frameworks, and resource indexes for synthetic data generation, covering tabular, relational, time-series, and privacy-preserving synthesis.

## 1. Individual Methods and Implementations

The table links method names to implementation repositories. Research implementations and reusable model packages are both included. Descriptions summarize implementation scope and do not imply validated superiority.

| Method / Implementation | Method Family / Type | Description and Use | Code Repository |
| --- | --- | --- | --- |
| ARF | Adversarial random forest library | Supports density estimation and synthetic data generation using adversarial random forests. | [Repository](https://github.com/bips-hb/arf) |
| CTGAN / TVAE | GAN / VAE implementation library | Implements conditional GAN and variational autoencoder models for mixed-type single-table synthesis. | [Repository](https://github.com/sdv-dev/CTGAN) |
| CTAB-GAN | GAN research implementation | Implements conditional generation for mixed-type, skewed, and imbalanced tabular data. | [Repository](https://github.com/Team-TUD/CTAB-GAN) |
| CTAB-GAN+ | GAN research implementation | Uses specialized encodings and training objectives for mixed-type tabular synthesis. | [Repository](https://github.com/Team-TUD/CTAB-GAN-Plus) |
| CTAB-GAN+ DP | Differentially private GAN implementation | Provides the differentially private version of CTAB-GAN+ for privacy-constrained synthesis. | [Repository](https://github.com/Team-TUD/CTAB-GAN-Plus-DP) |
| tableGAN | GAN research implementation | Implements an early GAN-based approach to tabular synthesis for historical baseline comparisons. | [Repository](https://github.com/mahmoodm2/tableGAN) |
| medGAN | Discrete data generation implementation | Generates binary and count-valued patient records; represents an early approach to discrete tabular synthesis. | [Repository](https://github.com/mp2893/medgan) |
| GOGGLE | Dependency-aware generation implementation | Learns relationships among variables to support tabular generation and prior-knowledge incorporation. | [Repository](https://github.com/tennisonliu/GOGGLE) |
| TAEGAN | GAN research implementation | Provides a tabular GAN method with data preparation and model training workflows. | [Repository](https://github.com/BetterdataLabs/taegan) |
| TabDDPM | Diffusion research implementation | Implements diffusion-based generation of numerical and categorical table variables. | [Repository](https://github.com/yandex-research/tab-ddpm) |
| STaSy | Score-based generation implementation | Implements score-based tabular synthesis with training, fine-tuning, and evaluation procedures. | [Repository](https://github.com/JayoungKim408/STaSy) |
| CoDi | Contrastive diffusion implementation | Jointly models continuous and discrete variables through co-evolving diffusion processes. | [Repository](https://github.com/ChaejeongLee/CoDi) |
| FinDiff | Financial tabular diffusion implementation | Generates mixed-type financial tabular data using diffusion models. | [Repository](https://github.com/sattarov/FinDiff) |
| FairTabDDPM | Balanced and fairness-oriented synthesis implementation | Supports balanced mixed-type synthesis for studying group representation and fairness-aware augmentation. | [Repository](https://github.com/comp-well-org/fair-tab-diffusion) |
| TabSyn | Latent diffusion research implementation | Combines a variational autoencoder with score-based diffusion in latent space. | [Repository](https://github.com/amazon-science/tabsyn) |
| TabDiff | Mixed-type diffusion research implementation | Models heterogeneous numerical and categorical variables through diffusion. | [Repository](https://github.com/MinkaiXu/TabDiff) |
| ForestDiffusion | Tree-based diffusion / flow implementation | Uses gradient-boosted trees for diffusion- and flow-based tabular generation and imputation. | [Repository](https://github.com/SamsungSAILMontreal/ForestDiffusion) |
| TabNAT | Continuous–discrete generation implementation | Combines continuous-variable diffusion with discrete-variable prediction in a joint generation framework. | [Repository](https://github.com/fangliancheng/TabNAT) |
| TabbyFlow / EF-VFM | Flow matching research implementation | Generates mixed-type tabular data using exponential-family variational flow matching. | [Repository](https://github.com/andresguzco/ef-vfm) |
| TabSynFlow | Flow matching research implementation | Provides flow matching methods and comparative experiments for tabular synthesis. | [Repository](https://github.com/rulnasution/tabular-flow-matching) |
| TabRep | Tabular diffusion research implementation | Uses continuous representations to train diffusion models for tabular generation. | [Repository](https://github.com/jacobyhsi/TabRep) |
| TabCascade | Cascaded flow matching implementation | Generates heterogeneous tabular data through cascaded flow matching. | [Repository](https://github.com/muellermarkus/tabcascade) |
| GReaT | Language-model synthesis library | Adapts pretrained language models to generate synthetic tabular records. | [Repository](https://github.com/tabularis-ai/be_great) |
| Tabula | Language-model synthesis implementation | Uses efficient tabular encoding to shorten sequences for language-model-based synthesis. | [Repository](https://github.com/zhao-zilong/Tabula) |
| REaLTabFormer | Transformer synthesis library | Uses autoregressive and sequence-to-sequence Transformers for tabular and relational synthesis. | [Repository](https://github.com/worldbank/REaLTabFormer) |
| DataSynthesizer | Privacy-oriented synthesis library | Provides random, independent-attribute, and correlated-attribute generation modes with differential privacy mechanisms. | [Repository](https://github.com/DataResponsibly/DataSynthesizer) |
| Twinify | Privacy-preserving synthesis library | Generates privacy-preserving synthetic versions of sensitive datasets. | [Repository](https://github.com/DPBayes/twinify) |
| DPSynth | Differentially private synthesis library | Provides differentially private tabular synthesis using marginal measurements and Private-PGM inference. | [Repository](https://github.com/google/dpsynth) |
| ClavaDDPM | Multi-relational diffusion implementation | Uses cluster-guided diffusion to synthesize relational tables while modeling cross-table dependencies. | [Repository](https://github.com/weipang142857/ClavaDDPM) |
| GRDM / rdb-diffusion | Relational database generation implementation | Uses graph-conditioned diffusion to model row attributes and dependencies across relational tables. | [Repository](https://github.com/ketatam/rdb-diffusion) |
| TimeGAN | Time-series generation implementation | Combines representation learning, supervised objectives, and adversarial training to generate temporal sequences. | [Repository](https://github.com/jsyoon0823/TimeGAN) |
| DoppelGANger | Time-series generation implementation | Generates time series together with associated metadata for longitudinal and behavioral data applications. | [Repository](https://github.com/fjxmlzn/DoppelGANger) |

## 2. Additional Engines, Supporting Frameworks, and Resource Indexes

These resources complement the individual methods above and are not counted as standalone methods in Section 1. Resource indexes are discovery aids rather than primary evidence for methodological claims.

| Resource | Type | Description and Use | URL |
| --- | --- | --- | --- |
| MOSTLY AI Engine | Integrated generation engine | Provides an engine for tabular and sequential synthetic data generation, including configurable privacy-related functionality. | [Repository](https://github.com/mostly-ai/mostlyai-engine) |
| YData Synthetic / fg-data-synthetic | Integrated synthesis library | Provides tabular and time-series generators; the listed repository is associated with the former YData Synthetic project. | [Repository](https://github.com/Data-Centric-AI-Community/fg-data-synthetic) |
| Gretel Synthetics | Synthesis library | Provides structured and unstructured data generators, including implementations useful for reproducing earlier approaches. | [Repository](https://github.com/gretelai/gretel-synthetics) |
| Diffprivlib | Supporting differential privacy library | Provides private statistics, mechanisms, and machine learning components for privacy-aware workflows. | [Repository](https://github.com/IBM/differential-privacy-library) |
| TensorFlow Privacy | Supporting private training library | Supports differentially private training of TensorFlow models, including components for private generative modeling. | [Repository](https://github.com/tensorflow/privacy) |
| Opacus | Supporting private training library | Supports differentially private training of PyTorch models and custom generative architectures. | [Repository](https://github.com/meta-pytorch/opacus) |
| Flower | Supporting federated learning framework | Coordinates distributed and cross-institutional training; synthesis models require separate implementation. | [Repository](https://github.com/flwrlabs/flower) |
| MIDSTModels | Privacy challenge reference implementations | Provides single-table and multi-table diffusion models for membership inference research. | [Repository](https://github.com/VectorInstitute/MIDSTModels) |
| Comprehensive Survey of Synthetic Tabular Data Generation | Survey resource index | Collects papers and code links covering traditional methods, GANs, VAEs, diffusion, and language models. | [Repository](https://github.com/ruxueshi/Awesome-Comprehensive-Survey-of-Synthetic-Tabular-Data-Generation) |
| Diffusion and Flow Matching Models for Tabular Data | Specialized resource index | Collects research on diffusion, flow matching, relational synthesis, imputation, and trustworthy generation. | [Repository](https://github.com/Diffusion-Model-Leiden/awesome-diffusion-models-for-tabular-data) |
| Gretel Awesome Synthetic Data | General resource index | Collects synthetic data tools, papers, and application resources. | [Repository](https://github.com/gretelai/awesome-synthetic-data) |
| Awesome Data Synthesis | General resource index | Collects synthesis methods, implementations, and evaluation resources. | [Repository](https://github.com/joofio/awesome-data-synthesis) |

## 3. Usage and Reproducibility Notes

- **Scope of inclusion:** Inclusion does not establish suitability for a particular dataset, validated superiority, or citation coverage in an accompanying manuscript.
- **Application-specific validation:** A method originally developed for healthcare, networking, or general tabular data is not automatically a credit-risk method.
- **Source attribution:** Cite the corresponding method paper and the implementation actually used. Distinguish original author repositories from third-party implementations and integrated library versions.
- **Resource indexes:** Use indexes to discover papers and software. Refer to original papers and implementation documentation as primary evidence for methodological claims.
- **Version control:** Record the exact repository commit or release and dependency versions.
- **Experimental configuration:** Document preprocessing, data splits, random seeds, hyperparameters, synthetic sample sizes, and evaluation settings.
- **Data leakage prevention:** Fit preprocessing procedures and generators using the designated training data. Keep final real test data separate from model fitting and selection.
- **Privacy reporting:** Where differential privacy is claimed, report the privacy definition, neighboring relation, privacy budget, accounting method, and protected processing stages.
- **Repository terms:** Consult each repository for its license, installation instructions, supported features, and maintenance status.
