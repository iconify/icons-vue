<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wtkd5updk"/><path class="bx7n1_b8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hub-add" /></template>
<style>
.bx7n1_b8y {
  d: path("M3 8.25v3.5q0 .11.01.221q.01.11.031.22t.051.219q.031.11.071.218q.041.108.092.215q.05.108.111.213q.061.106.131.21t.15.206t.169.202t.188.197q.098.098.205.192q.108.095.224.187q.115.092.24.181q.124.088.256.174q.133.085.273.167t.288.16q.147.078.302.152q.154.074.316.145q.161.07.329.135q.167.066.341.128q.173.061.352.118t.363.109t.373.099t.381.089t.389.08t.397.069q.199.032.402.059q.202.027.407.049q.204.021.411.037q.206.017.414.027q.208.011.416.017q.208.005.417.005q.684 0 1.359-.058m6.877-3.328Q20 12.316 20 11.75v-3.5m-12.75 0a4.25 1.75 0 1 0 8.5 0a4.25 1.75 0 1 0-8.5 0M18 15v6m-3-3h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wtkd5updk {
  d: path("M3 8.25a8.5 4.5 0 1 0 17 0a8.5 4.5 0 1 0-17 0");
}

</style>
