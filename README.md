# workflow

Proyecto base en **Flutter** (Dart) generado con la plantilla oficial. Sirve como punto de partida para una aplicación multiplataforma.

## Estado del proyecto

Actualmente el repositorio contiene la aplicación de ejemplo de Flutter (un contador con `MaterialApp` y un `StatefulWidget`) y una prueba de widget asociada. Aún no incluye funcionalidades propias.

## Estructura

```
workflow/
└── workflow/            # Proyecto Flutter
    ├── lib/main.dart    # Punto de entrada de la app
    ├── test/            # Pruebas de widgets
    ├── android/         # Proyecto Android (Kotlin)
    ├── web/             # Soporte web
    ├── windows/         # Soporte Windows
    ├── linux/           # Soporte Linux
    ├── macos/           # Soporte macOS
    └── pubspec.yaml     # Dependencias y configuración
```

## Requisitos

- [Flutter SDK](https://docs.flutter.dev/get-started/install) compatible con Dart `^3.13.5` (ver `pubspec.yaml`)
- Un emulador, dispositivo físico o navegador para ejecutar la app

## Cómo ejecutarlo

```bash
git clone https://github.com/yafAram/workflow.git
cd workflow/workflow
flutter pub get
flutter run
```

Para ejecutar las pruebas:

```bash
flutter test
```

## Próximos pasos

- [ ] Definir el objetivo funcional de la aplicación
- [ ] Reemplazar la pantalla de ejemplo por la interfaz real
- [ ] Agregar pruebas propias
- [ ] Configurar integración continua con GitHub Actions (`flutter analyze` y `flutter test`)

## Autor

**Yafté Aram Mercado Meza** · [GitHub](https://github.com/yafAram)
