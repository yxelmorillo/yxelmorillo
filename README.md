🌐 Idiomas: [Español](#versión-en-español) | [English](#english-version)

---

# Versión en Español

# Hola, soy Yxel Morillo 👋

## Business & Data Analyst | Socio Estratégico de Datos

Transformo problemas de negocio en análisis estructurados, dashboards claros y recomendaciones accionables.

Mi trabajo se mueve en la intersección entre:

**Negocio + Datos + Estrategia Comercial**

Utilizo SQL, Power BI, Looker Studio, Excel y Google Sheets para responder preguntas como:

- ¿Dónde está perdiendo dinero el negocio?
- ¿Qué está impulsando o frenando el rendimiento?
- ¿Dónde se están cayendo clientes u oportunidades?
- ¿Qué KPIs realmente importan?
- ¿Qué equipos, productos, canales o procesos requieren atención?
- ¿Qué decisión debería tomar el negocio después del análisis?

Mi objetivo no es ser solamente alguien que escribe queries.

Quiero ser el analista que entiende **por qué el análisis importa, qué decisión debe apoyar y cómo comunicarlo de forma clara para que alguien pueda actuar.**

---

# Cómo pienso el análisis

Mi enfoque parte de una idea sencilla:

> **Primero entender el problema de negocio. Después elegir la herramienta.**

Antes de abrir SQL o construir un dashboard, intento responder:

1. ¿Qué problema estamos intentando resolver?
2. ¿Quién necesita la respuesta?
3. ¿Qué decisión se va a tomar con esta información?
4. ¿Qué datos tenemos realmente?
5. ¿Qué reglas de negocio necesitamos definir?
6. ¿Qué muestra la evidencia?
7. ¿Qué acción debería seguir?

Después utilizo los datos para avanzar desde:

```text
Problema de Negocio
        ↓
Validación de Datos
        ↓
Análisis
        ↓
Hallazgo
        ↓
Recomendación
        ↓
Decisión
```

---

# Casos Destacados

Estos proyectos están construidos como **casos de negocio completos**, no como ejercicios aislados de SQL.

Cada uno comienza con una pregunta de un stakeholder y termina con hallazgos y recomendaciones.

---

## 1. Análisis de Salud del Pipeline Comercial

### ¿Dónde estamos perdiendo oportunidades y qué impacto tiene sobre el negocio?

El Gerente Comercial estaba preocupado porque demasiadas oportunidades no terminaban convirtiéndose en ventas.

El objetivo fue identificar:

- dónde se ralentiza el pipeline;
- dónde se pierden oportunidades;
- cuánto valor potencial está en riesgo;
- y si determinados vendedores requieren una revisión adicional.

### Qué analicé

- Reconstrucción del pipeline a partir del historial de etapas
- Transiciones entre fases
- Advance Rate
- Loss Rate
- Tiempo promedio y mediano entre etapas
- Valor potencial perdido
- Performance por vendedor
- Deal Size como posible factor explicativo

### Hallazgos principales

- Las primeras transiciones tardan aproximadamente **13–14 días**.
- Proposal y Negotiation aumentan a aproximadamente **20–21 días**.
- Negotiation presenta el mayor Loss Rate, cercano al **37%**.
- Discovery concentra el mayor impacto económico, con aproximadamente **$572M de valor potencial de pipeline perdido**.
- Algunos vendedores presentan Loss Rates considerablemente superiores al promedio incluso después de considerar Deal Size.

### Recomendaciones

- Reforzar el proceso de Discovery.
- Estandarizar Negotiation.
- Implementar coaching dirigido en lugar de capacitación genérica.
- Monitorear KPIs de Pipeline Health de forma continua.

### Herramientas

`SQL Server` `T-SQL` `Google Sheets` `Looker Studio` `Business Analysis`

🔗 [Ver caso completo](https://github.com/yxelmorillo/sales-pipeline-health-analysis)

---

## 2. Análisis de Performance Comercial y Customer Lifetime Value

### ¿Quiénes son realmente los mejores vendedores?

Revenue por sí solo no siempre identifica al vendedor que genera más valor para el negocio.

Este caso evalúa performance comercial combinando adquisición de clientes y valor de largo plazo.

### Qué analicé

- Clientes adquiridos
- Revenue inicial
- Customer Lifetime Value
- Average Customer Lifetime Value
- Atribución de clientes a vendedores
- Normalización de monedas
- Calidad de datos
- Reglas de negocio

### Desafío analítico

El revenue del cliente no podía asignarse simplemente utilizando el estado final del CRM.

Fue necesario definir reglas de negocio para determinar:

- el primer pago exitoso;
- la oportunidad correcta de adquisición;
- el vendedor responsable;
- y el Lifetime Value posterior del cliente.

### Valor para el negocio

El análisis permite evaluar performance de una forma más completa:

> **No solo quién vende más, sino quién adquiere clientes de mayor valor para el negocio.**

### Herramientas

`SQL Server` `T-SQL` `Power BI` `Business Analytics` `Customer LTV`

🔗 [Ver caso completo](https://github.com/yxelmorillo/sales-performance-analysis)

---

## 3. Análisis de Ventas Ecommerce — Olist

### ¿Qué está impulsando el rendimiento del ecommerce?

Utilizando el dataset público de ecommerce brasileño Olist, analicé el negocio desde diferentes perspectivas.

### Preguntas de negocio

- ¿Cómo está evolucionando el revenue?
- ¿Qué productos y categorías generan más ingresos?
- ¿Dónde se concentran las ventas y los clientes?
- ¿Qué sellers pueden representar valor comercial o riesgo operativo?

### Qué analicé

- Revenue trends
- Performance de productos
- Performance de categorías
- Concentración geográfica
- Comportamiento de clientes
- Seller performance
- Ventas canceladas y perdidas
- Indicadores de riesgo operativo

### Valor para el negocio

El caso conecta datos transaccionales con decisiones relacionadas con:

- estrategia de producto;
- prioridades de inventario;
- expansión regional;
- monitoreo de sellers;
- experiencia del cliente.

### Herramientas

`SQL` `Excel / Google Sheets` `Power BI / Looker Studio` `Ecommerce Analytics`

🔗 [Ver caso completo](https://github.com/yxelmorillo/ecommerce-sales-analysis-olit)

---

## 4. Análisis de Performance de Marketing Ads

### ¿Cómo debería una empresa distribuir su presupuesto publicitario?

Este proyecto analiza campañas digitales para entender si la inversión en marketing está generando resultados eficientes.

### Preguntas de negocio

- ¿Aumentar el gasto está produciendo un crecimiento proporcional?
- ¿Qué campañas deberían recibir más presupuesto?
- ¿Qué canales y campañas son más eficientes?
- ¿Cómo comparar campañas con objetivos diferentes?

### Qué analicé

- Marketing Spend
- Clicks
- CTR
- CPC
- Campaign Performance
- Budget Share
- Channel Efficiency
- Performance por objetivo de campaña

### Valor para el negocio

El objetivo no fue simplemente identificar campañas con mayor volumen.

La intención fue detectar cuáles presentan el mejor equilibrio entre:

> **Performance + Eficiencia + Potencial de Escala**

### Herramientas

`SQL` `Google Sheets` `Looker Studio` `Marketing Analytics`

🔗 [Ver caso completo](https://github.com/yxelmorillo/marketing-ads-performance-analysis)

---

# Qué Demuestran Estos Proyectos

A través de estos casos he practicado el flujo completo de Analytics.

## Entendimiento del Negocio

Transformar preocupaciones amplias de stakeholders en preguntas de negocio medibles.

## Calidad de Datos

Identificar:

- valores faltantes;
- duplicados;
- categorías inconsistentes;
- relaciones rotas;
- IDs inválidos;
- problemas de fechas y horas;
- historiales incompletos.

## Data Cleaning

Preparar y normalizar datos utilizando:

- Google Sheets
- Excel
- SQL

## SQL

Trabajo con:

- `JOIN`
- `CTE`
- `CASE`
- `GROUP BY`
- Conditional Aggregation
- Window Functions
- `LEAD()`
- `LAG()`
- `ROW_NUMBER()`
- `DATEDIFF()`
- Percentiles / Median
- Data Quality Checks
- Transformaciones basadas en reglas de negocio

## Diseño de KPIs

Definir métricas a partir del problema de negocio, no simplemente porque el dataset permite calcularlas.

Algunos ejemplos:

- Advance Rate
- Loss Rate
- Pipeline Value Lost
- Customer Lifetime Value
- Average Deal Size
- Sales Rep Performance
- Revenue Performance
- Marketing Efficiency

## Data Visualization

Construcción de dashboards en:

- Power BI
- Looker Studio

con foco en responder preguntas concretas de stakeholders.

## Comunicación de Negocio

Traducir análisis en:

- hallazgos;
- riesgos;
- oportunidades;
- recomendaciones;
- próximos pasos.

---

# Mi Forma de Pensar como Analista

Un análisis técnicamente correcto puede seguir siendo inútil si no ayuda a tomar una decisión.

Por eso intento separar tres cosas.

## Lo que los datos muestran

La evidencia observable.

## Lo que los datos sugieren

Una hipótesis razonable respaldada por evidencia.

## Lo que los datos no demuestran

Factores que requieren investigación adicional antes de concluir causalidad.

Por ejemplo:

Un vendedor con Loss Rate elevado no es automáticamente un mal vendedor.

Antes de llegar a esa conclusión analizaría:

- Deal Size;
- complejidad de las oportunidades;
- perfil de cliente;
- etapa del pipeline;
- pricing;
- objeciones;
- proceso comercial;
- tamaño de la muestra.

Esa distinción entre **observación, interpretación y causalidad** es una parte central de cómo intento trabajar con datos.

---

# Stack Técnico

## Data & Analysis

- SQL Server
- T-SQL
- Excel
- Google Sheets
- Data Cleaning
- Data Validation
- Exploratory Data Analysis
- KPI Design

## Business Intelligence

- Power BI
- Looker Studio
- Dashboard Design
- Data Visualization
- Data Storytelling
- Executive Reporting

## Business & Commercial Analytics

- Sales Analytics
- Revenue Operations
- Funnel / Pipeline Analysis
- Customer Lifetime Value
- Marketing Analytics
- Ecommerce Analytics
- Process Analysis

## Otras Herramientas

- CRM
- Google Ads
- Meta Business Manager
- Email Marketing
- Notion
- Git
- GitHub

---

# Qué Aporto Más Allá de las Herramientas

Mi background incluye negocio, project management, consultoría y resolución de problemas comerciales.

Eso cambia la forma en la que abordo los datos.

En lugar de comenzar preguntando:

> “¿Qué query debería escribir?”

prefiero empezar por:

> **“¿Qué decisión estamos intentando tomar?”**

Y después determinar qué análisis realmente hace falta.

Me interesan especialmente entornos donde Analytics trabaje cerca de:

- Ventas
- Operaciones
- Revenue
- Management
- Producto
- Marketing
- Founders
- Stakeholders de negocio

---

# Roles a los que Apunto

Mi portfolio está especialmente alineado con:

- Data Analyst
- Business Analyst
- Business Data Analyst
- Revenue Operations Analyst
- BI Analyst
- Operations Analyst
- Sales Analyst
- Analytics Consultant

Me interesan especialmente roles donde el análisis técnico se combine con:

> **Entendimiento de Negocio + Pensamiento Analítico + Comunicación con Stakeholders**

---

# Filosofía de Portfolio

Estoy construyendo mi portfolio intencionalmente alrededor de problemas completos de negocio.

No:

```text
Dataset
→ Query
→ Gráfico
```

Sino:

```text
Pregunta de Negocio
        ↓
Entender el Proceso
        ↓
Validar los Datos
        ↓
Definir Reglas de Negocio
        ↓
Analizar
        ↓
Visualizar
        ↓
Encontrar el Insight
        ↓
Recomendar una Acción
```

Ese es el tipo de analista que estoy desarrollando.

---

# En Qué Sigo Profundizando

Continúo fortaleciendo mis habilidades en:

- SQL avanzado;
- Power BI;
- Looker Studio;
- Business Analysis;
- Commercial Analytics;
- Data Modeling;
- Dashboard Design;
- Analytical Storytelling;
- flujos de trabajo asistidos por IA.

Creo que la IA va a automatizar cada vez más partes del trabajo analítico.

Eso hace que habilidades como:

- entender el negocio;
- formular correctamente el problema;
- validar;
- pensar críticamente;
- comunicar;
- apoyar decisiones;

sean todavía más importantes.

Esas son las capacidades que estoy desarrollando junto con las herramientas técnicas.

---

# Contacto

Estoy abierto a oportunidades en:

**Data Analytics · Business Analytics · BI · Revenue Operations · Sales Analytics**

📍 Argentina / Remote

💼 [LinkedIn — Yxel Morillo](https://www.linkedin.com/in/yxel-morillo/)

💻 [GitHub — yxelmorillo](https://github.com/yxelmorillo)

📧 **yxelmorilloconsultor@gmail.com**

---

# English Version

# Hi, I'm Yxel Morillo 👋

## Business & Data Analyst | Strategic Data Partner

I turn business problems into structured analysis, clear dashboards, and actionable recommendations.

My work sits at the intersection of:

**Business + Data + Commercial Strategy**

I use SQL, Power BI, Looker Studio, Excel, and Google Sheets to answer questions such as:

- Where is the business losing money?
- What is driving or hurting performance?
- Where are customers or opportunities dropping off?
- Which KPIs actually matter?
- Which teams, products, channels, or processes require attention?
- What should the business do next?

My goal is not to become someone who only writes queries.

I want to be the analyst who understands **why the analysis matters, what decision it should support, and how to communicate it clearly.**

---

# How I Approach Analytics

My approach starts with a simple principle:

> **Understand the business problem first. Choose the tool second.**

Before opening SQL or building a dashboard, I try to understand:

1. What problem are we trying to solve?
2. Who needs the answer?
3. What decision will be made with the information?
4. What data do we actually have?
5. What business rules need to be defined?
6. What does the evidence show?
7. What action should follow?

Then I use data to move from:

```text
Business Problem
        ↓
Data Validation
        ↓
Analysis
        ↓
Insight
        ↓
Recommendation
        ↓
Decision
```

---

# Featured Business Cases

These projects are designed as **complete business case studies**, not isolated SQL exercises.

Each one starts with a stakeholder question and ends with findings and recommendations.

---

## 1. Sales Pipeline Health Analysis

### Where are we losing opportunities, and what is the business impact?

A Sales Manager was concerned that too many opportunities were failing to convert into sales.

The goal was to identify:

- where the pipeline slows down;
- where opportunities are being lost;
- how much potential pipeline value is at risk;
- and whether specific sales representatives require additional attention.

### What I Analyzed

- Pipeline reconstruction using stage history
- Stage-to-stage transitions
- Advance Rate
- Loss Rate
- Average and median transition time
- Pipeline Value Lost
- Sales Rep Performance
- Deal Size as a possible explanatory factor

### Key Findings

- Early-stage transitions took approximately **13–14 days**.
- Proposal and Negotiation increased to approximately **20–21 days**.
- Negotiation had the highest Loss Rate at approximately **37%**.
- Discovery represented the greatest economic impact, with approximately **$572M in potential pipeline value lost**.
- Some sales representatives showed significantly higher Loss Rates even after considering Deal Size.

### Business Recommendations

- Strengthen Discovery.
- Standardize Negotiation.
- Implement targeted coaching instead of generic training.
- Continuously monitor Pipeline Health KPIs.

### Tools

`SQL Server` `T-SQL` `Google Sheets` `Looker Studio` `Business Analysis`

🔗 [View the full case study](https://github.com/yxelmorillo/sales-pipeline-health-analysis)

---

## 2. Sales Performance & Customer Lifetime Value Analysis

### Who are the company's best sales representatives?

Revenue alone does not always identify the salesperson generating the greatest business value.

This case evaluates performance using customer acquisition and long-term customer value.

### What I Analyzed

- Customers Acquired
- Initial Revenue
- Customer Lifetime Value
- Average Customer Lifetime Value
- Sales Rep Attribution
- Currency Normalization
- Data Quality
- Business Rules

### Analytical Challenge

Customer revenue could not simply be assigned using the final CRM status.

Business rules were required to determine:

- the first successful customer payment;
- the correct acquisition opportunity;
- the responsible sales representative;
- and the customer's subsequent Lifetime Value.

### Business Value

The analysis provides a more complete way to evaluate sales performance:

> **Not only who sells the most, but who acquires the most valuable customers.**

### Tools

`SQL Server` `T-SQL` `Power BI` `Business Analytics` `Customer LTV`

🔗 [View the full case study](https://github.com/yxelmorillo/sales-performance-analysis)

---

## 3. Ecommerce Sales Analysis — Olist

### What is driving ecommerce performance?

Using the public Brazilian Olist ecommerce dataset, I analyzed the business from multiple perspectives.

### Business Questions

- How is revenue evolving?
- Which products and categories drive the most revenue?
- Where are customers and sales geographically concentrated?
- Which sellers may represent commercial value or operational risk?

### What I Analyzed

- Revenue Trends
- Product Performance
- Category Performance
- Geographic Concentration
- Customer Behavior
- Seller Performance
- Cancelled and Lost Sales
- Operational Risk Indicators

### Business Value

The case connects transactional ecommerce data with decisions involving:

- product strategy;
- inventory priorities;
- regional growth;
- seller monitoring;
- customer experience.

### Tools

`SQL` `Excel / Google Sheets` `Power BI / Looker Studio` `Ecommerce Analytics`

🔗 [View the full case study](https://github.com/yxelmorillo/ecommerce-sales-analysis-olit)

---

## 4. Marketing Ads Performance Analysis

### How should a business allocate its advertising budget?

This project analyzes digital advertising campaigns to understand whether marketing investment is producing efficient results.

### Business Questions

- Is increasing ad spend producing proportional performance?
- Which campaigns deserve additional budget?
- Which channels and campaigns are more efficient?
- How should campaigns with different objectives be compared?

### What I Analyzed

- Marketing Spend
- Clicks
- CTR
- CPC
- Campaign Performance
- Budget Share
- Channel Efficiency
- Performance by Campaign Objective

### Business Value

The goal was not simply to identify campaigns with the highest volume.

The objective was to identify campaigns with the strongest balance between:

> **Performance + Efficiency + Scalability**

### Tools

`SQL` `Google Sheets` `Looker Studio` `Marketing Analytics`

🔗 [View the full case study](https://github.com/yxelmorillo/marketing-ads-performance-analysis)

---

# What These Projects Demonstrate

Across these cases, I have practiced the full analytics workflow.

## Business Understanding

Turning broad stakeholder concerns into measurable business questions.

## Data Quality

Identifying:

- missing values;
- duplicates;
- inconsistent categories;
- broken relationships;
- invalid IDs;
- date and time issues;
- incomplete historical records.

## Data Cleaning

Preparing and normalizing data using:

- Google Sheets
- Excel
- SQL

## SQL

Working with:

- `JOIN`
- `CTE`
- `CASE`
- `GROUP BY`
- Conditional Aggregation
- Window Functions
- `LEAD()`
- `LAG()`
- `ROW_NUMBER()`
- `DATEDIFF()`
- Percentiles / Median
- Data Quality Checks
- Business-rule-driven transformations

## KPI Design

Defining metrics based on the actual business question rather than calculating metrics simply because the data allows it.

Examples include:

- Advance Rate
- Loss Rate
- Pipeline Value Lost
- Customer Lifetime Value
- Average Deal Size
- Sales Rep Performance
- Revenue Performance
- Marketing Efficiency

## Data Visualization

Building dashboards in:

- Power BI
- Looker Studio

with a focus on answering specific stakeholder questions.

## Business Communication

Translating analysis into:

- findings;
- risks;
- opportunities;
- recommendations;
- next actions.

---

# My Analytical Mindset

A technically correct analysis can still be useless if it does not help someone make a decision.

For that reason, I try to separate three things.

## What the Data Shows

Observable evidence.

## What the Data Suggests

A reasonable hypothesis supported by evidence.

## What the Data Does Not Prove

Factors that require additional investigation before claiming causality.

For example:

A sales representative with a high Loss Rate is not automatically a poor performer.

Before reaching that conclusion, I would investigate:

- Deal Size;
- opportunity complexity;
- customer profile;
- pipeline stage;
- pricing;
- objections;
- sales process;
- sample size.

That distinction between **observation, interpretation, and causality** is central to how I approach analytics.

---

# Technical Toolkit

## Data & Analysis

- SQL Server
- T-SQL
- Excel
- Google Sheets
- Data Cleaning
- Data Validation
- Exploratory Data Analysis
- KPI Design

## Business Intelligence

- Power BI
- Looker Studio
- Dashboard Design
- Data Visualization
- Data Storytelling
- Executive Reporting

## Business & Commercial Analytics

- Sales Analytics
- Revenue Operations
- Funnel / Pipeline Analysis
- Customer Lifetime Value
- Marketing Analytics
- Ecommerce Analytics
- Process Analysis

## Additional Tools

- CRM
- Google Ads
- Meta Business Manager
- Email Marketing
- Notion
- Git
- GitHub

---

# What I Bring Beyond the Tools

My background includes business, project management, consulting, and commercial problem-solving.

That changes how I approach data.

Instead of starting with:

> “What query should I write?”

I prefer to start with:

> **“What decision are we trying to make?”**

Then I determine what analysis is actually necessary.

I am particularly interested in environments where Analytics works closely with:

- Sales
- Operations
- Revenue
- Management
- Product
- Marketing
- Founders
- Business Stakeholders

---

# Roles I'm Building Toward

My portfolio is particularly aligned with:

- Data Analyst
- Business Analyst
- Business Data Analyst
- Revenue Operations Analyst
- BI Analyst
- Operations Analyst
- Sales Analyst
- Analytics Consultant

I am especially interested in roles where technical analysis is combined with:

> **Business Understanding + Analytical Thinking + Stakeholder Communication**

---

# Portfolio Philosophy

I am intentionally building my portfolio around complete business problems.

Not:

```text
Dataset
→ Query
→ Chart
```

But:

```text
Business Question
        ↓
Understand the Process
        ↓
Validate the Data
        ↓
Define Business Rules
        ↓
Analyze
        ↓
Visualize
        ↓
Find the Insight
        ↓
Recommend an Action
```

That is the type of analyst I am becoming.

---

# What I'm Continuing to Improve

I continue strengthening my skills in:

- advanced SQL;
- Power BI;
- Looker Studio;
- Business Analysis;
- Commercial Analytics;
- Data Modeling;
- Dashboard Design;
- Analytical Storytelling;
- AI-assisted analytics workflows.

I believe AI will increasingly automate parts of analytics work.

That makes capabilities such as:

- understanding the business;
- framing the problem correctly;
- validation;
- critical thinking;
- communication;
- decision support;

even more important.

Those are the capabilities I am deliberately developing alongside technical tools.

---

# Let's Connect

I'm open to opportunities in:

**Data Analytics · Business Analytics · BI · Revenue Operations · Sales Analytics**

📍 Argentina / Remote

💼 [LinkedIn — Yxel Morillo](https://www.linkedin.com/in/yxel-morillo/)

💻 [GitHub — yxelmorillo](https://github.com/yxelmorillo)

📧 **yxelmorilloconsultor@gmail.com**
