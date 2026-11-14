<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ab_v4wbas"/><path class="m45b313xm"/><path class="g4zsb_bea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-add-on" /></template>
<style>
.ab_v4wbas {
  d: path("M3.5 5a8 2.5 0 1 0 16 0a8 2.5 0 1 0-16 0Z");
}

.g4zsb_bea {
  d: path("M3.5 11.5q0 .061.01.123q.009.061.029.122q.019.061.048.122q.028.061.067.121q.038.06.086.119q.047.06.104.119t.124.116q.066.058.141.115q.075.056.159.112q.084.055.177.109q.092.055.193.107q.101.053.21.104t.226.1t.242.097t.256.093t.271.089t.285.084q.145.042.297.081q.152.038.309.075q.158.037.321.071q.164.034.332.065q.169.032.342.061t.351.055t.359.05q.181.023.366.044t.373.038t.378.033t.383.027q.193.012.387.021t.39.015t.391.009q.197.003.393.003q.953 0 1.88-.07t1.774-.206m4.036-1.535q.31-.338.31-.689M18 15v6m-3-3h6");
}

.m45b313xm {
  d: path("M3.5 5v13q0 .061.01.123q.009.061.029.122q.019.061.048.122q.028.061.067.121q.038.06.086.119q.047.06.104.119t.124.116q.066.058.141.115q.075.056.159.112q.084.055.177.109q.092.055.193.107q.101.053.21.104t.226.1t.242.097t.256.093t.271.089t.285.084q.145.042.297.081q.152.038.309.075q.158.037.321.071q.164.034.332.065q.169.032.342.061t.351.055t.359.05t.366.044t.373.038t.378.033t.383.027t.387.021t.39.015t.391.009q.197.003.393.003q.325 0 .649-.008M19.5 12.21V5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
