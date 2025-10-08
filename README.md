💬 Análisis de Sentimientos y Discurso en Comentarios de YouTube — Proyecto NLP

Este proyecto representa un punto de inflexión en mi camino como científica de datos: fue la primera red neuronal que entrené y la experiencia que despertó en mí un profundo interés por el campo del Procesamiento del Lenguaje Natural (NLP).
Además, aborda un tema contemporáneo y socialmente relevante: cómo el contenido cultural y los discursos digitales influyen en la construcción de vínculos, identidades y percepciones colectivas.

🎯 Objetivo del proyecto

Analizar los comentarios de un video de YouTube donde una creadora realiza un análisis sociológico de la saga Crepúsculo, con especial foco en cómo la serie de libros y películas moldeó los patrones relacionales y los roles de género en una generación de jóvenes.

El objetivo técnico y analítico fue doble:

Explorar el sentimiento general y las emociones expresadas en los comentarios del video.

Evaluar las limitaciones actuales de los modelos de análisis de sentimientos, especialmente frente a textos cargados de ironía, sarcasmo, lenguaje informal y emojis, características muy presentes en la comunicación digital contemporánea.

🧠 Desafíos y aprendizajes

Durante el desarrollo del proyecto enfrenté varios retos significativos:

El dataset contenía comentarios con alto nivel de sarcasmo y tono hostil, especialmente hacia la autora del video (una mujer trans). Esto dificultó el reconocimiento emocional, ya que los modelos preentrenados no siempre comprenden el contexto social o las sutilezas del lenguaje humano.

Algunos algoritmos de clasificación emocional confundían ironía con neutralidad o positividad, lo que abrió la reflexión sobre la necesidad de mejorar los modelos para adaptarlos a nuevas normas lingüísticas y culturales.

Implementar un pipeline NLP completo —desde la extracción vía API hasta la limpieza, tokenización, análisis y modelado— me permitió consolidar habilidades técnicas y al mismo tiempo entender la dimensión ética del análisis automatizado del lenguaje.

🧩 Herramientas y tecnologías utilizadas

Python

pandas, numpy → Procesamiento y estructuración de datos

nltk, spacy, textblob, transformers → Análisis y modelado de texto

tensorflow / keras → Entrenamiento de red neuronal

matplotlib, wordcloud, plotly → Visualizaciones y nubes de palabras

API de YouTube Data → Extracción automática de comentarios

Google Colab → Desarrollo y documentación

GitHub → Control de versiones y publicación del proyecto

🔍 Proceso general

Obtención de datos desde la API de YouTube.

Limpieza y preprocesamiento del texto: eliminación de stopwords, normalización de emojis, detección de sarcasmo y símbolos.

Análisis exploratorio del lenguaje: frecuencia de palabras, polaridad, temas recurrentes.

Entrenamiento de un modelo de red neuronal para detección de emociones.

Evaluación de resultados y reflexión crítica sobre los sesgos y limitaciones del modelo.

🌈 Resultados y reflexión final

El proyecto no solo permitió entrenar mi primera red neuronal, sino también abrir una reflexión sobre el rol del lenguaje digital, la ironía y la discriminación en los espacios online.

Descubrí que los modelos de NLP, por más avanzados que sean, todavía no comprenden completamente las sutilezas humanas —y ahí es donde quiero enfocar mi futuro: en mejorar la empatía algorítmica de las herramientas de análisis de texto.

Mi objetivo a largo plazo es contribuir al desarrollo de modelos de NLP más inclusivos y contextualmente conscientes, que puedan captar la emocionalidad real detrás de las palabras y no solo su forma literal.

👀 Cómo explorar el proyecto

📓 Notebook principal: Proyecto_final_3_Yasmin_Osorio_Vilariño_LIMPIO_FINAL.ipynb

🎥 Fuente de datos: API del video original de YouTube

📊 Resultados y visualizaciones: se encuentran documentados dentro del notebook

💬 Invitación

Si te interesa el NLP, la ética en IA o el análisis de discurso digital, te invito a explorar este proyecto.
Es un trabajo hecho con mucha pasión, curiosidad y compromiso por entender cómo las emociones, la cultura y la tecnología se entrelazan en los espacios digitales.

Toda sugerencia o intercambio de ideas es más que bienvenido 🤝
