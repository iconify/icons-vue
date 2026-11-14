<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="srh6vmbhx"/><path class="y5-g4g2mx"/><path class="ugylfj4yr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cost-up" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.srh6vmbhx {
  d: path("M2.5 6.5a8.5 2.5 0 1 0 17 0a8.5 2.5 0 1 0-17 0");
}

.ugylfj4yr {
  d: path("M2.5 10a8.5 2.5 0 0 0 17 0M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

.y5-g4g2mx {
  d: path("M2.5 6.5v7q0 .061.01.123q.01.061.031.122t.051.122q.031.061.071.121q.041.06.092.119q.05.06.111.119t.131.116t.15.115q.08.056.169.112q.089.055.188.109q.098.055.205.107q.108.053.224.104q.115.051.24.1t.256.097q.133.047.273.093q.14.045.288.089q.147.043.302.084q.154.042.316.081q.161.038.329.075q.167.037.341.071q.173.034.352.065q.179.032.363.061t.373.055t.381.05q.193.023.389.044q.197.021.397.038q.199.018.402.033q.202.015.407.027t.411.021t.414.015t.416.009T11 16q1.139 0 2.238-.088m6.262-3.261V6.5");
}

</style>
