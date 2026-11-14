<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h6h7z1bhr"/><path class="tcvm1xbxe"/><path class="abxqzvbqc"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:backup-schedule" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.abxqzvbqc {
  d: path("M3.5 11.25q0 .061.009.123q.009.061.027.122t.045.122t.063.121t.081.119t.098.119q.053.058.115.116t.133.115q.07.056.149.112q.079.055.166.109q.086.055.181.107q.095.053.197.104t.212.1t.226.097t.241.093t.254.089t.266.084q.137.042.279.081q.142.038.29.075t.301.071t.311.065q.158.032.321.061q.162.029.328.055q.167.026.337.05q.17.023.343.044t.35.038t.355.033t.359.027q.18.012.363.021q.182.009.365.015t.367.009t.368.003q1.51 0 2.902-.195m4.325-1.636q.273-.328.273-.669M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.h6h7z1bhr {
  d: path("M3.5 5.5a7.5 2.5 0 1 0 15 0a7.5 2.5 0 1 0-15 0Z");
}

.tcvm1xbxe {
  d: path("M3.5 5.5V17q0 .061.009.123q.009.061.027.122t.045.122t.063.121t.081.119t.098.119q.053.058.115.116t.133.115t.149.112t.166.109q.086.055.181.107q.095.053.197.104t.212.1t.226.097t.241.093t.254.089t.266.084q.137.042.279.081q.142.038.29.075t.301.071t.311.065q.158.032.321.061q.162.029.328.055q.167.026.337.05q.17.023.343.044t.35.038q.176.018.355.033q.178.015.359.027q.18.012.363.021q.182.009.365.015t.367.009t.368.003q.569 0 1.131-.029m6.369-7.498V5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
