<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ggj859bnz"/><path class="u6v-jybjq"/><path class="wrl8gubxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-table-plus" /></template>
<style>
.ggj859bnz {
  d: path("M2.5 5a8 2.5 0 1 0 16 0a8 2.5 0 1 0-16 0Z");
}

.u6v-jybjq {
  d: path("M2.5 5v13.5q0 .061.01.123q.009.061.029.122q.019.061.048.122q.028.061.067.121q.038.06.086.119q.047.06.104.119t.124.116q.066.058.141.115q.075.056.159.112q.084.055.177.109q.092.055.193.107q.101.053.21.104t.226.1t.242.097t.256.093t.271.089t.285.084q.145.042.297.081q.152.038.309.075q.158.037.321.071q.164.034.332.065q.169.032.342.061t.351.055t.359.05t.366.044t.373.038t.378.033q.191.015.383.027q.193.012.387.021t.39.015t.391.009q.197.003.393.003q1.815 0 3.451-.245M18.5 12.21V5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wrl8gubxf {
  d: path("M2.5 11.75q0 .061.01.123q.009.061.029.122q.019.061.048.122q.028.061.067.121q.038.06.086.119q.047.06.104.119t.124.116q.066.058.141.115q.075.056.159.112q.084.055.177.109q.092.055.193.107q.101.053.21.104t.226.1t.242.097t.256.093t.271.089t.285.084q.145.042.297.081q.152.038.309.075q.158.037.321.071q.164.034.332.065q.169.032.342.061t.351.055t.359.05q.181.023.366.044t.373.038t.378.033q.191.015.383.027q.193.012.387.021t.39.015t.391.009q.197.003.393.003q.633 0 1.259-.031t1.227-.093t1.165-.152t1.074-.207m3.156-1.587q.119-.213.119-.43m-8 2.5V21m7.5-6v6m-3-3h6");
}

</style>
