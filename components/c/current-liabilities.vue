<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n5q96udht"/><path class="yzfu16bdr"/><path class="vgbb_cbwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:current-liabilities" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n5q96udht {
  d: path("M3 4.5a6.5 2 0 1 0 13 0a6.5 2 0 1 0-13 0");
}

.vgbb_cbwp {
  d: path("M3 7.75a6.5 2 0 0 0 13 0M3 11a6.5 2 0 0 0 13 0m.75 4.5h2.5A1.75 1.75 0 0 1 21 17.25v2.25a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.5v-2.25a1.75 1.75 0 0 1 1.75-1.75M15 17.75h6m-4.25-3.25V16m2.5-1.5V16");
}

.yzfu16bdr {
  d: path("M3 4.5v9.75q0 .049.008.098t.023.098t.039.097t.055.097t.07.096t.085.095t.1.093t.115.091t.129.09t.144.088q.075.043.157.085t.17.083q.089.041.184.08q.095.04.196.078t.209.074t.22.071t.231.068t.241.064t.252.06t.261.057q.132.027.269.052q.137.026.278.049t.285.044t.292.04t.297.035q.15.017.303.031t.308.026t.311.022t.314.016t.317.012l.318.008q.159.002.319.002q1.491 0 2.833-.2M16 11.81V4.5");
}

</style>
