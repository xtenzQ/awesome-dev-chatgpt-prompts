# 💡 Awesome Developer GPT Prompts

<img src="https://img.shields.io/badge/status-work_in_progress-green" />
<img src="https://img.shields.io/badge/gpt-4o+-blue" />

Welcome to **Awesome Developer GPT Prompts** – a curated collection of prompts designed specifically to enhance your developer workflow and productivity. Whether you're brainstorming complex logic, writing documentation, or looking to optimize your code, these prompts aim to provide quick and actionable guidance.

Feel free to explore the prompts, submit your own ideas, and contribute to the repo. Let’s collaborate and create a go-to resource for every developer’s GPT-driven toolkit!

This repo is still in WIP.

# 📍 Preparations

I highly recommend to create a separate project in ChatGPT and use prompts below as instructions. To understand how to create a project, use this [**link**](https://help.openai.com/en/articles/10169521-using-projects-in-chatgpt).

```text
You are an all-in-one expert software architect with the following characteristics:

1. Role & Responsibilities:
   - Principal Architect responsible for designing end-to-end solutions for a wide variety of applications (web, mobile, enterprise, data platforms, AI/ML systems, etc.).
   - Overseer of best practices in software development, machine learning lifecycle, data engineering, DevOps, cybersecurity, QA, and documentation.
   - Mentor and thought leader for development teams, providing guidance on coding standards, architectural patterns, and emerging technologies.

2. Qualifications & Experience:
   - 10+ years of full-stack development experience across multiple languages and frameworks (e.g., Java, Python, JavaScript/TypeScript, C#, Go, etc.).
   - Deep expertise in cloud platforms (AWS, Azure, GCP), container orchestration (Docker, Kubernetes), and microservices architecture.
   - Advanced knowledge of data pipelines, ETL, database design (SQL & NoSQL), and data warehousing solutions (e.g., Snowflake, Redshift, BigQuery).
   - Proficiency in machine learning frameworks (TensorFlow, PyTorch, scikit-learn) and MLOps best practices.
   - Experience in writing and refining prompts for LLMs (like ChatGPT) and integrating AI services into existing systems.

3. Architectural & Technical Approaches:
   - Employ proven architectural patterns: microservices, serverless, event-driven, hexagonal/clean architecture, etc.
   - Prioritize scalability, reliability, and security at every layer.
   - Utilize DevOps principles (CI/CD pipelines, Infrastructure as Code, automated testing, containerization).
   - Implement robust QA strategies, from unit testing to integration, performance, and security testing.
   - Practice Agile/Scrum or DevOps-oriented workflows for rapid iteration and continuous improvement.

4. Knowledge Areas & Special Focus:
   - Software Engineering: SOLID principles, design patterns, code review best practices, clean coding.
   - Machine Learning: data collection, preprocessing, model training, hyperparameter tuning, deployment, and monitoring.
   - Prompt Engineering: design and optimize prompts for large language models, ensuring reliability, accuracy, and interpretability.
   - Quality Assurance: automated testing frameworks (JUnit, pytest, Cypress, etc.), QA tools, best practices for test coverage.
   - Security & Compliance: knowledge of OWASP best practices, encryption, identity management, and relevant regulations (GDPR, HIPAA, PCI-DSS).

5. Constraints & Goals:
   - You are designing architectures for different types of applications. Each solution must address business requirements, scalability, performance, security, maintainability, and cost-effectiveness.
   - Architecture should include diagrams or detailed text-based breakdowns of components, data flow, and integration points.
   - Provide justification for design decisions, highlight potential trade-offs, and recommend best-in-class technologies.

6. Communication Style:
   - Always explain the reasoning behind recommendations and design patterns.
   - Present information in a structured, step-by-step manner, with headings or bullet points where possible.
   - Use concise, clear, and technically sound language suitable for stakeholders of varying technical backgrounds.

Given these characteristics, your task is to produce detailed architectural designs and strategies for the requested application or system. You may ask clarifying questions where necessary, enumerate assumptions, outline technology choices, propose a high-level design, and then delve into an in-depth explanation of each layer/component.
```

## 📒 Prompts

### Daily routine

#### Refactoring & Code Cleanup

```text
 Please refactor the following {Language} code that uses the {Framework} framework. 
- Use {Plugin/Tool} (if applicable) for linting or static analysis.
- Retain current functionality.

[PASTE YOUR CODE HERE]
```

#### Performance Optimization

```text
Our application is experiencing slow response times under heavy load. 
- We use Language} and {Framework}.
- Identify bottlenecks and propose specific changes to improve performance.
- Consider using {Plugin/Tool} (e.g., profilers, performance analyzers) if relevant.
- Provide insights on caching, concurrency, or data structure improvements.
- Explain trade-offs and ensure the changes remain cost-effective.

[OPTIONAL: SHARE CODE SNIPPETS OR SCENARIO]
```

#### Code Quality & Best Practices Review

```text
Review the following code written using {Language} and {Framework} for:
2. Clean coding principles (naming, structure, readability).
3. Best practices and design patterns.
4. Potential bugs or antipatterns.
5. Opportunities to simplify or modularize the code.
6. Compliance with {Plugin/Tool} (e.g., ESLint, Checkstyle) configurations.

[PASTE YOUR CODE HERE]
```

#### Design Pattern Implementation

```text
We have a codebase in {Language} using {Framework}, and we want to introduce the {Design Pattern} pattern (e.g., Factory, Singleton, Observer, etc.).
- Show how to refactor or integrate the {Design Pattern} into our existing code.
- Explain the benefits and potential trade-offs.
- Suggest any relevant {Plugin/Tool} or library that might simplify this pattern.

[OPTIONAL: PASTE YOUR CODE OR EXPLAIN YOUR CURRENT ARCHITECTURE]
```

#### Database Query & Schema Optimization

```text
Our {Database} queries are slow or returning inconsistent results. 
- Provide recommendations to optimize our SQL/NoSQL queries.
- Suggest any schema changes or indexing strategies.
- Consider using {Tool/Plugin} (e.g., EXPLAIN ANALYZE, indexing advisors) if available.
- Outline potential impacts on our {Framework} application.

[PASTE SAMPLE QUERIES OR EXPLAIN SCHEMA HERE]
```

#### Security Hardening & Audit

```text
- Perform a security audit of our code, looking for common vulnerabilities (e.g., XSS, SQL injection, CSRF).
- Suggest improvements or additional checks (e.g., using {Plugin/Tool}, adopting best practices like OWASP Top 10).
- Propose a plan for ongoing vulnerability scanning and penetration testing.

[PASTE YOUR CODE OR SECURITY CONCERNS HERE]
```

#### CI/CD Pipeline Enhancement

```text
Our {Language}-{Framework} application needs a robust CI/CD pipeline.
- Suggest improvements for code integration, building, testing, and deployment.
- Integrate {Plugin/Tool} for automated code analysis, security scans, and artifact management.
- Provide a high-level YAML or configuration file example, if relevant.
- Explain how to handle rollbacks and environment-specific deployments.
```

#### Testing Strategy & Coverage Improvement

```text
We use {Language}, {Framework}, and {Test Framework} in our QA.
- Assess our current testing strategy and coverage.
- Recommend additional test types (unit, integration, E2E) and how to implement them.
- Suggest {Plugin/Tool} for coverage reports and test automation.
- Provide sample test cases or configurations.

[OPTIONAL: SHARE CODE OR TEST RESULTS HERE]
```

####  API & Microservices Performance Review

```text
We have a microservices architecture built with {Language} on {Framework}. We are experiencing latency and potential bottlenecks in our API layer. 
- Analyze our service-to-service communication, data serialization, and network overhead.
- Propose optimizations (e.g., caching, asynchronous messaging, circuit breakers).
- Recommend any {Plugin/Tool} for load testing and distributed tracing.
- Provide a high-level diagram or explanation of the improved architecture.

[OPTIONAL: DESCRIBE YOUR CURRENT MICROSERVICES SETUP]
```

### General scenarios

#### E-commerce Microservices Platform

```text
Design an architecture for a high-traffic e-commerce platform with AI-driven product 
recommendations. The platform should be based on microservices, deployed on 
a cloud provider, and capable of handling seasonal spikes. We need to 
incorporate a recommendation engine and a robust DevOps pipeline. Please 
include details on the data flow, caching strategy, load balancing
service-to-service communication, CI/CD, and QA testing approaches.
```

#### Enterprise Data Lake & Analytics

```text
Propose an end-to-end architecture for an enterprise data lake and analytics platform.
We need to ingest data from multiple internal and external sources (IoT devices, CRM,
social media APIs). The platform should support real-time data processing,
transformations, and both structured and unstructured data. We also want to
incorporate an ML pipeline for predictive analytics. Outline data storage options,
the ETL/ELT process, security considerations, and how different teams can access
the analytics layer.
```

#### Mobile Banking App with Security Emphasis

```text
We’re designing a mobile banking application focusing on security and performance.
Provide an architecture that ensures compliance with financial regulations (e.g.,
PCI-DSS, GDPR) and includes advanced security measures like encryption, MFA, and
fraud detection. Show how the backend services, data storage, and integration with
third-party financial services should be structured. Also outline how to implement
a robust QA strategy (including regression and penetration testing).
```

#### Global SaaS Platform with Multi-Region Deployment

```text
We need a global SaaS application that runs in multiple regions (US, EU, APAC) with
low latency and high availability. It should have a modular microservices design,
support multi-tenancy, and automatically scale to handle diverse usage patterns.
Provide details on the best database approach (SQL/NoSQL or hybrid), caching
strategies, region failover, and recommended technology stack. Also discuss DevOps
best practices for multi-region deployments.
```

#### Legacy System Modernization

```text
We have a large legacy monolithic application currently running on on-premises
servers. We want to migrate to a cloud-native microservices or serverless
architecture (whichever is more suitable) while maintaining business continuity.
Describe a phased migration plan, highlight any refactoring needed, and propose
a high-level architecture. Include details on data migration, integration with
existing systems, and a testing and rollback strategy.
```

#### AI Chatbot Integration

```text
Our customer support platform needs an AI chatbot integration. We want it to leverage
a large language model and have a feedback loop for continuous improvement. Provide a
reference architecture showing how the chatbot, NLP pipeline, and user data
interact. Include a plan for logging conversations, training new models, and
ensuring data privacy. Additionally, specify best practices for deployment and
versioning of the chatbot service.
```

#### Observability & Monitoring Strategy 

```text
We want to establish a comprehensive observability and monitoring strategy across a
microservices-based platform. Outline how logs, metrics, and traces should be
collected and aggregated. Discuss the recommended tooling (e.g., Prometheus,
Grafana, ELK stack, OpenTelemetry) and how alerts should be configured. Provide 
an architecture diagram showing how each service publishes logs/metrics, how we
set up dashboards, and how teams handle incident response.
```

#### Healthcare Application with Compliance and Machine Learning

```text
Create an architecture for a healthcare application that uses machine learning to
predict patient readmissions. The system must comply with HIPAA and handle sensitive
patient data securely. Include data ingestion, cleaning, ML model training, and
deployment strategies. Highlight user authentication and authorization, encryption,
auditing logs, and how you would handle compliance requirements (e.g., data
residency, de-identification).
```

#### Serverless Event-Driven Application

```text
We want a serverless, event-driven system to process real-time streams of user
activity data (e.g., clicks, page views, location) and generate analytics dashboards.
Propose a cloud-native architecture that uses managed services for event ingestion,
processing, and storage. Detail how to handle sudden spikes in traffic, how the
data flows through serverless functions, and how to integrate with a real-time
analytics dashboard.
```

#### Custom CRM Platform with AI-driven Insights

```text
We are building a custom CRM platform for a mid-sized organization. The CRM should
track leads, manage customer interactions, and use AI/ML to provide lead-scoring and
sales forecasting. Outline a modular, scalable architecture (microservices vs. a
monolith?), the data model, and how to incorporate an ML pipeline. Specify
recommended DevOps processes, QA strategies, and performance benchmarks to aim for.
```

## 🤝 Contribution
I'd love to accept your contributions to this project. I use GitHub pull requests for this purpose. Consult [GitHub Help](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) for more information on using pull requests.

## 🧡 Find this repository useful?
Please support it by joining __[stargazers](https://github.com/xtenzQ/awesome-dev-chatgpt-prompts/stargazers)__ for this repository. :star:
