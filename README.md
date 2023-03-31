# FlashForge 3D Printer

[![GitHub Release][releases-shield]][releases]
[![GitHub Activity][commits-shield]][commits]
[![License][license-shield]](LICENSE)

[![hacs][hacsbadge]][hacs]

_Integration to integrate with [FlashForge][flashforge]._

**This integration will set up the following platforms.**

Platform | Description
-- | --
`binary_sensor` | Show something `True` or `False`.
`sensor` | Show info from blueprint API.
`switch` | Switch something `True` or `False`.

## Installation

1. Using the tool of choice open the directory (folder) for your HA configuration (where you find `configuration.yaml`).
1. If you do not have a `custom_components` directory (folder) there, you need to create it.
1. In the `custom_components` directory (folder) create a new folder called `flashforge`.
1. Download _all_ the files from the `custom_components/flashforge/` directory (folder) in this repository.
1. Place the files you downloaded in the new directory (folder) you created.
1. Restart Home Assistant
1. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "FlashForge"

## Configuration is done in the UI

<!---->

## Contributions are welcome!

If you want to contribute to this please read the [Contribution guidelines](CONTRIBUTING.md)

***

[flashforge]: https://github.com/joseffallman/hass_flashforge
[commits-shield]: https://img.shields.io/github/commit-activity/y/joseffallman/hass_flashforge.svg?style=for-the-badge
[commits]: https://github.com/joseffallman/hass_flashforge/commits/main
[hacs]: https://github.com/hacs/integration
[hacsbadge]: https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge
[exampleimg]: example.png
[license-shield]: https://img.shields.io/github/license/joseffallman/hass_flashforge.svg?style=for-the-badge
[releases-shield]: https://img.shields.io/github/release/joseffallman/hass_flashforge.svg?style=for-the-badge
[releases]: https://github.com/joseffallman/hass_flashforge/releases
