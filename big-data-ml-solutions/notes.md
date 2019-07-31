# Azure Machine Learning

Azure Machine Learning Studio is a collaborative, drag-and-drop tool for building, testing, and deploying predictive analytics solutions on your data.

Microsoft Azure Machine Learning Studio is a collaborative, drag-and-drop tool you can use to build, test, and deploy predictive analytics solutions on your data. Machine Learning Studio publishes models as web services that can easily be consumed by custom apps or BI tools such as Excel.

Machine Learning Studio is where data science, predictive analytics, cloud resources, and your data meet.

The Machine Learning Studio interactive workspace
To develop a predictive analysis model, you typically use data from one or more sources, transform, and analyze that data through various data manipulation and statistical functions, and generate a set of results. Developing a model like this is an iterative process. As you modify the various functions and their parameters, your results converge until you are satisfied that you have a trained, effective model.

Azure Machine Learning Studio gives you an interactive, visual workspace to easily build, test, and iterate on a predictive analysis model. You drag-and-drop datasets and analysis modules onto an interactive canvas, connecting them together to form an experiment, which you run in Machine Learning Studio. To iterate on your model design, you edit the experiment, save a copy if desired, and run it again. When you're ready, you can convert your training experiment to a predictive experiment, and then publish it as a web service so that your model can be accessed by others.

![Azure ML](https://docs.microsoft.com/en-us/azure/machine-learning/studio/media/what-is-ml-studio/azure-ml-studio-diagram.jpg "Azure ML")

## Managing Related Resources

You can manage resources using Projects in Azure Machine Learning Studio where all assets (experiments,datasets,notebooks etc) can be stored.

## Cortana Intelligent Gallery

## Azure ML Major Components

- **Projects** - Collections of experiments, datasets, notebooks and other resources representing a single project
- **Experiemnts** - Experiments that you have created and run or saved as drafts
- **Web Services** - Web services that you have deployed from your experiments
- **Notebooks** - Jupyter notebooks that you have created
- **Datasets** - Datasets that you have uploaded into Studio
- **Trained Models** - Models that you have trained in experiemnts and saved in Studio
- **Settings** - A collection of settings that you can use to configure your account and resources.

An experiment consists of datasets that provide data to analytical modules, which you connect together to sonctruct a predictive analysis model.

A module is an algorithm that you can perform on your data. Machine Learning Studio has a number of modules ranging from data ingree functions to training, scoring and validation processes. A module may have a set of parameters that you can use to configure the module's internal algorithms.

## Working with Big Data Sources

### types of Data sources

You can import a number of data types into your experiment

- Plain text(.txt)
- Comma-separated values (CSV) with a header (.csv) or without (.nh.csv)
- Tab-separated values (TSV) with a header (.tsv) or without (.nh.tsv)
- Excel file
- Azure table
- Hive table
- SQL database table
- OData values
- SVMLight data (.svmlight) (see the SVMLight definition for format information)
- Attribute Relation File Format (ARFF) data (.arff) (see the ARFF definition for format information)
- Zip file (.zip)
- R object or workspace file (.RData)

## Further Reading

- https://docs.microsoft.com/en-us/azure/machine-learning/studio/import-data
- https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/prepare-data  - preprocessing data tasks
