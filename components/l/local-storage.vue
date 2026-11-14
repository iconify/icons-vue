<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pbuexb_va"/><path class="zrbjazmdw"/><path class="aarl__gyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:local-storage" /></template>
<style>
.aarl__gyb {
  d: path("M3 11.5q0 .061.009.123q.009.061.027.122t.045.122t.063.121t.081.119t.098.119q.053.058.115.116t.133.115q.07.056.149.112q.079.055.166.109q.086.055.181.107q.095.053.197.104t.212.1t.226.097t.241.093t.254.089t.266.084q.137.042.279.081q.142.038.29.075t.301.071t.311.065q.158.032.321.061q.162.029.328.055q.167.026.337.05q.17.023.343.044t.35.038t.355.033t.359.027q.18.012.363.021q.182.009.365.015t.367.009t.368.003q1 0 1.965-.087m5.262-1.744Q18 11.841 18 11.5M16 15h4a1.75 1.75 0 0 1 1.75 1.75v3A1.75 1.75 0 0 1 20 21.5h-4a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 16 15m3 3.25h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pbuexb_va {
  d: path("M3 5.5a7.5 2.5 0 1 0 15 0a7.5 2.5 0 1 0-15 0");
}

.zrbjazmdw {
  d: path("M3 5.5v12q0 .061.009.123q.009.061.027.122t.045.122t.063.121t.081.119t.098.119q.053.058.115.116t.133.115t.149.112t.166.109q.086.055.181.107q.095.053.197.104t.212.1t.226.097t.241.093t.254.089t.266.084q.137.042.279.081q.142.038.29.075t.301.071t.311.065q.158.032.321.061q.162.029.328.055q.167.026.337.05q.17.023.343.044t.35.038q.176.018.355.033q.178.015.359.027q.18.012.363.021q.182.009.365.015t.367.009t.368.003q.464 0 .924-.019M18 12.173V5.5");
}

</style>
