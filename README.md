# Deep-Learning-week15-Manipulaci-n-de-Datos-Monitoreo-y-Logging-y-Model-Serving-con-Weights-Biases

Análisis de Métricas y Valor del Monitoreo
Overfitting: Si train_acc >> val_acc, el modelo memoriza. El logging permite detectarlo tempranamente.
Estabilidad: Gráficas suaves de pérdida indican learning rate adecuado. Picos o oscilaciones sugieren necesidad de ajustar batch size o usar scheduler.
Trazabilidad: W&B registra hiperparámetros, métricas por epoch, pesos del modelo y entorno. Esto garantiza reproducibilidad y auditoría.
Decisión de despliegue: Solo se despliega un modelo con métricas estables en validación y sin sobreajuste significativo.
