# 📊 Análisis de Evasión de Clientes (Churn)

## 📌 Descripción del Proyecto

Este proyecto analiza la **evación de clientes (Churn)** en una empresa de telecomunicaciones mediante técnicas básicas de **Ciencia de Datos**.  
El churn ocurre cuando un cliente decide cancelar el servicio, lo que genera un impacto directo en los ingresos y en la estabilidad del negocio.

El objetivo principal del analísis es identificar patrones de comportamiento que permitan entender **por qué los clientes abandonan el servicio** y cómo se podrían tomar decisiones más estrategicas para reducir esta situación.

---

## 🎯 Objetivos

- Analizar el comportamiento de los clientes que cancelan el servicio.
- Identificar variables asociadas a una mayor probabilidad de churn.
- Generar insights útiles para apoyar decisiones de retención.

---

## 🗂️ Dataset

- **Fuente:** API pública en formato JSON  
- **Información incluida:**
  - Datos demográficos
  - Tipo de contrato
  - Servicios contratados
  - Tiempo de permanencia y cargos
  - Variable objetivo: `Churn` (1 = evadió, 0 = no evadió)

---

## 🧹 Limpieza y Tratamiento de Datos

Para preparar los datos se realizaron las siguientes tareas:

- Carga de datos desde una API y normalización del JSON.
- Conversión de variables categóricas (`Yes` / `No`) a valores numéricos (`1` / `0`).
- Tratamiento de valores como `No internet service` y `No phone service`.
- Corrección de tipos de datos para facilitar el análisis.
- Revisión de valores nulos e inconsistencias.

---

## 📈 Análisis Exploratorio de Datos (EDA)

El análisis exploratorio permitió identificar patrones relevantes mediante:

- Gráficos de barras para observar la distribución del churn.
- Comparación del churn según variables categóricas como tipo de contrato y servicios.
- Análisis de variables numéricas (tiempo de contrato y total gastado) entre clientes que evadieron y los que no.
- Visualizaciones creadas con **Matplotlib**.

---

## 🔍 Principales Insights

- Los clientes con contratos mensuales presentan mayor tasa de churn.
- Una menor antigüedad se asocia con mayor probabilidad de evación.
- Los clientes con menos servicios adicionales tienden a cancelar con más frecuencia.
- Un gasto acumulado bajo está relacionado con mayor evasión.

---

## 💡 Recomendaciones

- Incentivar contratos de mayor duración.
- Promover servicios adicionales que aumenten el valor percibido.
- Implementar acciones tempranas para clientes nuevos.
- Utilizar este análisis como base para futuros modelos predictivos.

---

## 🛠️ Tecnologías Utilizadas

- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook  

---

## 👤 Autor

**Yadir Cubillo**  
Proyecto realizado como parte de un proceso de aprendizaje en Ciencia de Datos.
