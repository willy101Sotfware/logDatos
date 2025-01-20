# Proyecto de Procesamiento de Logs

Este proyecto procesa un archivo de log (`Log2025-01-17.json`), extrae información relevante y la organiza en un archivo JSON (`LogOrganizado.json`). Además, genera un archivo Excel (`datos_analizados.xlsx`) y una gráfica de frecuencia de recibos.

## Requisitos

Asegúrate de tener Python 3.x instalado en tu sistema. Este proyecto utiliza las siguientes bibliotecas:

- `pandas`
- `matplotlib`
- `openpyxl`

## Instalación de Dependencias

Puedes instalar las dependencias necesarias utilizando `pip`. Ejecuta el siguiente comando en tu terminal:

```bash
pip install -r requirements.txt
```

## Estructura del Proyecto

```
.
├── README.md
├── requirements.txt
├── Datos.py
├── Log2025-01-17.json
└── datos_analizados.xlsx
```

## Uso

Ejecuta el script principal `Datos.py`:

```bash
python Datos.py
```

El script procesará el archivo de log y generará:
1. Un archivo JSON organizado (`LogOrganizado.json`)
2. Un archivo Excel con los datos analizados (`datos_analizados.xlsx`)
3. Una gráfica de frecuencia de recibos

## Licencia

Este proyecto está bajo la Licencia MIT.
