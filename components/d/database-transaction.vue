<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="debaxmbpp"/><path class="vkegz3bdf"/><path class="r2k-w4czb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-transaction" /></template>
<style>
.debaxmbpp {
  d: path("M3 5a6.5 2.5 0 1 0 13 0A6.5 2.5 0 1 0 3 5Z");
}

.r2k-w4czb {
  d: path("M3 9.5a6.5 2.5 0 0 0 13 0m-1 6.75h6m-1.75-1.75L21 16.25m0 3.5h-6m1.75 1.75L15 19.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vkegz3bdf {
  d: path("M3 5v9q0 .061.008.123q.008.061.023.122q.016.061.039.122q.024.061.055.121t.07.119t.085.119q.046.058.1.116t.115.115q.061.056.129.112q.068.055.144.109q.075.055.157.107q.082.053.17.104t.184.1q.095.05.196.097t.209.093q.107.045.22.089q.113.043.231.084t.241.081q.124.038.252.075t.261.071q.132.034.269.065q.137.032.278.061t.285.055t.292.05t.297.044q.15.021.303.038q.153.018.308.033q.154.015.311.027q.156.012.314.021t.317.015t.318.009t.319.003q1.426 0 2.722-.23M16 13.404V5");
}

</style>
