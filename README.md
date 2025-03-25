# Azure_fabric_Earthquake_end_to_end
Azure Fabric Earthquake Data pipeline  project


# Beginner's Guide to Microsoft Fabric: Earthquake Data Pipeline

Welcome! This guide will walk you step-by-step through setting up a data pipeline using Microsoft Fabric. We’ll use an approach called the **medallion architecture** to organise earthquake data from raw to refined, making it easier for analysis. By the end of this guide, you’ll have an automated system that takes earthquake data from an API, processes it, and displays it in Power BI for easy insights—all updated daily!

### Business Case

Earthquake data is incredibly valuable for understanding seismic events and mitigating risks. Government agencies, research institutions, and insurance companies rely on up-to-date information to plan emergency responses and assess risks. With this automated pipeline, we ensure these stakeholders get the latest data in a way that’s easy to understand and ready to use, saving time and improving decision-making.

### Solution Overview

We're going to use **Microsoft Fabric** to build an end-to-end earthquake data pipeline using the **medallion architecture**.
