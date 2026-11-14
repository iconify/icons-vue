<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="chnmyzb6e"/><path class="fwodwob1l"/><path class="qz5iadcvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:legal-database" /></template>
<style>
.chnmyzb6e {
  d: path("M3 5a7.5 2.5 0 1 0 15 0A7.5 2.5 0 1 0 3 5");
}

.fwodwob1l {
  d: path("M3 5v13.5q0 .061.009.123q.009.061.027.122t.045.122t.063.121t.081.119t.098.119q.053.058.115.116t.133.115t.149.112t.166.109q.086.055.181.107q.095.053.197.104t.212.1t.226.097t.241.093t.254.089t.266.084q.137.042.279.081q.142.038.29.075t.301.071t.311.065q.158.032.321.061q.162.029.328.055q.167.026.337.05q.17.023.343.044t.35.038q.176.018.355.033q.178.015.359.027q.18.012.363.021q.182.009.365.015t.367.009t.368.003q.622 0 1.235-.034M18 11.073V5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qz5iadcvn {
  d: path("M3 9.5a7.5 2.5 0 0 0 15 0M3 14q0 .061.009.123q.009.061.027.122t.045.122t.063.121t.081.119t.098.119q.053.058.115.116t.133.115q.07.056.149.112q.079.055.166.109q.086.055.181.107q.095.053.197.104t.212.1t.226.097t.241.093t.254.089t.266.084q.137.042.279.081q.142.038.29.075t.301.071t.311.065q.158.032.321.061q.162.029.328.055q.167.026.337.05q.17.023.343.044t.35.038q.176.018.355.033q.178.015.359.027q.18.012.363.021q.182.009.365.015t.367.009t.368.003q1.394 0 2.695-.167m4.951-1.954l2.475 2.475a1.25 1.25 0 0 1 0 1.767a1.25 1.25 0 0 1-1.767 0l-2.475-2.475a1.25 1.25 0 0 1 0-1.767a1.25 1.25 0 0 1 1.767 0M17.5 17.5l-3 3");
}

</style>
