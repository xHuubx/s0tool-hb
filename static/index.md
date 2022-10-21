| Repository Status | ESPHome S0tool discord Community |
| :--- | :--- |
| [![last commit time][github-last-commit]][github-master] [![GitHub Activity][commits-shield]][commits] | [![Discord][discord-shield]][discord] ![Twitter Follow](https://img.shields.io/twitter/follow/huizebruin?style=social) 
|  [![License][license-shield]](LICENSE) [![Forks][forks-shield]][forks-url] [![Stargazers][stars-shield]][stars-url] [![Issues][issues-shield]][issues-url] | [![Contributors][contributors-shield]][contributors-url] [![GitHub release](https://img.shields.io/github/release/huizebruin/s0tool.svg)](https://GitHub.com/huizebruin/s0tool/releases/)| 

# S0tool

|  S0tool | Made for ESPHome program  |
| :--- | :--- |
|  ![S0tool-logo](./assets/s0tool-logo.jpg)  | ![ESPHome](./assets/made-for-esphome-black-on-white.png) |

Update : v2022-09-15 ( Date: 10/09/2022 ) <br><br>
With the<b> S0tool</b> you can keep track of the consumption of both your water meter and a kWh meter that has an S0 connection.

The tool is ideal for keeping track of the consumption of devices such as heat pumps, or the yield of your solar panels.
A suitable kWh meter with an S0 connection must be installed for this.

<b>S0tool</b> makes a *(not so)* kwh meter with a s0 port a smart meter, reading the pulse thats from the S0 port that is always present in most cases and it works with [ESPHome][esphome]!<br> And has a official Made for ESPHome licence <br>

![S0tool-and_case](./assets/S0tool_case.jpg) 

## Installation

You can use the button below to install the <b>S0tool</b> firmware directly to your device via USB from the browser.<br><br>

|  Version  Install   info  |<br>
|  S0tool standard:  <esp-web-install-button manifest="./s0tool-standard-manifest.json"></esp-web-install-button>
<script type="module" src="https://unpkg.com/esp-web-tools@5.2.0/dist/web/install-button.js?module"></script>  standard with watermeter and kwh meter |<br>
|  S0tool Watermeter:   <esp-web-install-button manifest="./s0tool-watermeter-manifest.json"></esp-web-install-button>
<script type="module" src="https://unpkg.com/esp-web-tools@5.2.0/dist/web/install-button.js?module"></script>  only watermeter |  <br>
|  S0tool 1000imp kWhmeter:   <esp-web-install-button manifest="./s0tool-1000imp-manifest.json"></esp-web-install-button>
<script type="module" src="https://unpkg.com/esp-web-tools@5.2.0/dist/web/install-button.js?module"></script>  only kwh meter 1000imp | <br>
|  S0tool 2000imp kWhmeter:   <esp-web-install-button manifest="./s0tool-2000imp-manifest.json"></esp-web-install-button>
<script type="module" src="https://unpkg.com/esp-web-tools@5.2.0/dist/web/install-button.js?module"></script>  only kwh meter 2000imp | <br>
|  S0tool dsz12d:   <esp-web-install-button manifest="./s0tool-dsz12d-manifest.json"></esp-web-install-button>
<script type="module" src="https://unpkg.com/esp-web-tools@5.2.0/dist/web/install-button.js?module"></script> special for the dsz12d | <br>
 <br>


***

## How to change the total readings
For the water counter: D2 [![Open your Home Assistant instance and show your service developer tools with a specific service selected.](https://my.home-assistant.io/badges/developer_call_service.svg)](https://my.home-assistant.io/redirect/developer_call_service/?service=ESPHome%3A+s0tool_meterstand_water)
<br><br>
For the S0 port of the kwh meter : D5  [![Open your Home Assistant instance and show your service developer tools with a specific service selected.](https://my.home-assistant.io/badges/developer_call_service.svg)](https://my.home-assistant.io/redirect/developer_call_service/?service=ESPHome%3A+s0tool_meterstand_kwh)

Or this one.
[![Open your Home Assistant instance and show your service developer tools with a specific service selected.](https://my.home-assistant.io/badges/developer_call_service.svg)](https://my.home-assistant.io/redirect/developer_call_service/?service=Nutsmeter%3A+Calibrate)
and you can find your readings and reset it. 

***

Have fun with the <b>S0tool</b>.<br>
 <br> For problems or solutions <b>[Pull requests](https://github.com/huizebruin/s0tool/pulls)</b>.<br> 
For problems <b>[issues](https://github.com/huizebruin/s0tool/issues) . </b><br>

 
<br><br><b>
Wobbe From Huizebruin.nl</b>
<br><br>
For more information about the S0tool look at my (Dutch) [website](https://www.huizebruin.nl/home-assistant/wat-is-de-s0tool/).
## License
MIT License

Copyright (c) 2021 / 2022 Huizebruin

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

***


[esphome]: https://esphome.io/
[commits-shield]: https://img.shields.io/github/commit-activity/m/huizebruin/s0tool.svg
[commits]: https://github.com/huizebruin/s0tool/commits/main
[github-last-commit]: https://img.shields.io/github/last-commit/huizebruin/s0tool.svg?style=plasticr
[github-master]: https://github.com/huizebruin/s0tool/commits/main
[license-shield]: https://img.shields.io/github/license/huizebruin/s0tool.svg
[discord-shield]: https://img.shields.io/discord/723629686093119650.svg?logo=discord&color=7289da
[discord]: https://discord.gg/bN8rC7gEng
[contributors-url]: https://github.com/huizebruin/s0tool/graphs/contributors
[contributors-shield]: https://img.shields.io/github/contributors/huizebruin/s0tool.svg
[forks-shield]: https://img.shields.io/github/forks/huizebruin/s0tool.svg
[forks-url]: https://github.com/huizebruin/s0tool/network/members
[stars-shield]: https://img.shields.io/github/stars/huizebruin/s0tool.svg
[stars-url]: https://github.com/huizebruin/s0tool/stargazers
[issues-shield]: https://img.shields.io/github/issues/huizebruin/s0tool.svg
[issues-url]: https://github.com/huizebruin/s0tool/issues
