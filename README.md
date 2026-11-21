<div align="center">

<img src="assets/banner.svg" alt="Yassine Emhamed, IT and Network Engineer" width="100%">

<br>

**IT and Network Engineer** in the DC, Maryland and Virginia area.
I build automation, websites and AI tooling that replace manual work.

<a href="https://www.yassine-emhamed.net"><img src="https://img.shields.io/badge/Portfolio-yassine--emhamed.net-8fb08a?style=for-the-badge&labelColor=14181c" alt="Portfolio"></a>
<a href="https://www.linkedin.com/in/yassine2emhamed/"><img src="https://img.shields.io/badge/LinkedIn-Connect-8fb08a?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=14181c" alt="LinkedIn"></a>
<a href="https://www.yassine-emhamed.net/card"><img src="https://img.shields.io/badge/Digital%20card-View-8fb08a?style=for-the-badge&labelColor=14181c" alt="Digital card"></a>

<br><br>

<img src="assets/stats.svg" alt="4+ years, 28 projects, 1,000+ work orders a month, no-shows cut from 28 to 9 percent" width="100%">

</div>

## What I build

<img src="assets/skills.svg" alt="Agentic automation, Python and APIs, Salesforce, web and apps, networks and systems, AI integrations" width="100%">

## Now

- Running **ArcaneDot**, a studio that has shipped 28 projects for 20+ clients, as Founder and CTO.
- Building **The DMV Hub**, a community site and Discord for DC, Maryland and Virginia.
- Program analyst on a DC government facilities team, running 1,000+ work orders a month across 900+ public buildings.
- Studying for the Salesforce Administrator exam, then Agentforce.

## Open source projects (30 repos)

Small, tested tools for facility, building and operations teams. Each repo has a README with real output, a screenshot, tests and CI.

### BIM, IFC and documents

| Repo | What it does |
|---|---|
| [bim-room-schedule-exporter](https://github.com/yassine2med/bim-room-schedule-exporter) | Reads an IFC file and writes that schedule as a CSV, with warnings for rooms that have no level, number or area. |
| [cobie-spreadsheet-validator](https://github.com/yassine2med/cobie-spreadsheet-validator) | Reads a COBie workbook and lists every missing sheet or column, broken reference, duplicate name and bad value. |
| [cobie-to-asset-register](https://github.com/yassine2med/cobie-to-asset-register) | Turns the Component, Type, Space, Floor and Facility sheets into a CSV with the columns of a facility asset register (the same columns as |

### Assets and capital planning

| Repo | What it does |
|---|---|
| [asset-lifecycle-forecaster](https://github.com/yassine2med/asset-lifecycle-forecaster) | Reads an asset list with install year, expected life and replacement cost, and prints how many assets and how much money fall due in each year. |
| [asset-register-template](https://github.com/yassine2med/asset-register-template) | Ships a JSON Schema for a facility asset, sample registers, and a small command line validator that reports each bad row and field. |
| [asset-tag-label-generator](https://github.com/yassine2med/asset-tag-label-generator) | Reads a CSV of assets and writes a PDF sheet of labels, three across and eight down on US Letter paper (2.5 by 1.25 inch each), with the asset ID |
| [backflow-test-reminder](https://github.com/yassine2med/backflow-test-reminder) | Reads a device list as CSV, computes each next due date and prints the list with the most urgent first. |
| [capital-plan-builder](https://github.com/yassine2med/capital-plan-builder) | Builds a plan of a chosen length (five years by default) from a CSV of assets. |
| [deferred-maintenance-ranker](https://github.com/yassine2med/deferred-maintenance-ranker) | Ranks a deferred maintenance backlog by risk and life safety, and picks the items that fit a budget. |
| [elevator-inspection-tracker](https://github.com/yassine2med/elevator-inspection-tracker) | Lists elevator and escalator certificates soonest expiry first, banded by days left. |
| [facility-condition-index](https://github.com/yassine2med/facility-condition-index) | Calculates the Facility Condition Index per building from a CSV of building systems. |

### Cost, contracts and procurement

| Repo | What it does |
|---|---|
| [bid-tabulation-tool](https://github.com/yassine2med/bid-tabulation-tool) | Compares contractor bids line by line and prices the scope each bidder left out, so the lowest bid is not just the most incomplete one. |
| [budget-vs-actual-report](https://github.com/yassine2med/budget-vs-actual-report) | Reads a budget CSV and an actuals CSV, adds up both from January through a chosen month, and prints the variance for each cost center and category |
| [change-order-log](https://github.com/yassine2med/change-order-log) | A SQLite log of construction change orders that keeps the running contract total, pending exposure and added days for each project. |
| [dc-building-permits-explorer](https://github.com/yassine2med/dc-building-permits-explorer) | Counts building permits and sums declared cost from a permit CSV, with a text bar chart. |

### Work orders and service desk

| Repo | What it does |
|---|---|
| [311-service-request-analyzer](https://github.com/yassine2med/311-service-request-analyzer) | Reads a service request CSV and prints, for each category, the count, open count, median and 90th percentile hours to close, and the age of the |
| [cmms-data-quality-auditor](https://github.com/yassine2med/cmms-data-quality-auditor) | Scores a work-order CSV from a CMMS for data quality, with a count per rule and a list of the worst records. |
| [cmms-export-cleaner](https://github.com/yassine2med/cmms-export-cleaner) | Normalizes a messy CMMS CSV export into a clean file plus a file of rejected rows. |
| [cmms-sql-cookbook](https://github.com/yassine2med/cmms-sql-cookbook) | Six SQL queries every maintenance team ends up writing: backlog by priority, aging buckets, MTTR, PM compliance, repeat failures and technician |
| [daily-log-builder](https://github.com/yassine2med/daily-log-builder) | Generate a construction daily report in Markdown from a JSON record of the site day. |
| [duplicate-workorder-detector](https://github.com/yassine2med/duplicate-workorder-detector) | Flags likely duplicate work orders in a CSV and groups them for review. |

### Building systems and air quality

| Repo | What it does |
|---|---|
| [building-energy-open-data-explorer](https://github.com/yassine2med/building-energy-open-data-explorer) | Loads such a table, computes site energy use intensity (EUI) for every building, ranks each one within its property type, and flags statistical |
| [co2-ventilation-estimator](https://github.com/yassine2med/co2-ventilation-estimator) | Does both with plain mass balance maths and the standard library only. |

### Safety, space and daily operations

| Repo | What it does |
|---|---|
| [bacnet-point-list-linter](https://github.com/yassine2med/bacnet-point-list-linter) | Reads a point list CSV and reports naming and object type problems line by line, so a building operations coordinator can send a clear correction |
| [bacnet-sim-logger](https://github.com/yassine2med/bacnet-sim-logger) | This small tool samples a list of BACnet style points on a fixed step and writes the readings to a CSV file. |
| [brick-model-builder](https://github.com/yassine2med/brick-model-builder) | Reads a plain equipment spreadsheet, checks it, and writes a Brick model in Turtle, so the same sheet a facility team already keeps can feed any |
| [cleaning-quality-score](https://github.com/yassine2med/cleaning-quality-score) | Turns cleaning inspection checklists into percentage scores, grades and a pass or fail per building or area. |
| [construction-schedule-gantt](https://github.com/yassine2med/construction-schedule-gantt) | Turn a CSV of construction tasks into a text Gantt chart and an optional SVG file. |
| [degree-day-normalizer](https://github.com/yassine2med/degree-day-normalizer) | Adjusts monthly utility use for weather using heating or cooling degree days. |
| [eui-calculator](https://github.com/yassine2med/eui-calculator) | Converts annual energy and floor area in mixed units to EUI in kBtu per square foot and kWh per square metre. |

## Stack

![Python](https://img.shields.io/badge/Python-14181c?style=flat-square&logo=python&logoColor=8fb08a)
![TypeScript](https://img.shields.io/badge/TypeScript-14181c?style=flat-square&logo=typescript&logoColor=8fb08a)
![Next.js](https://img.shields.io/badge/Next.js-14181c?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-14181c?style=flat-square&logo=react&logoColor=8fb08a)
![Salesforce](https://img.shields.io/badge/Salesforce-14181c?style=flat-square&logo=salesforce&logoColor=8fb08a)
![Claude](https://img.shields.io/badge/Claude%20API-14181c?style=flat-square&logo=anthropic&logoColor=8fb08a)
![Cisco](https://img.shields.io/badge/Cisco-14181c?style=flat-square&logo=cisco&logoColor=8fb08a)
![Vercel](https://img.shields.io/badge/Vercel-14181c?style=flat-square&logo=vercel&logoColor=white)

<div align="center">

<sub>English &middot; Fran&ccedil;ais &middot; &#1575;&#1604;&#1593;&#1585;&#1576;&#1610;&#1577; &nbsp;|&nbsp; Silver Spring, MD</sub>

</div>
