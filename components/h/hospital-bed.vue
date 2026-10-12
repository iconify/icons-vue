<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gplilobog"/><circle class="akzn_2afg"/><path class="tdx_tmbvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hospital-bed" /></template>
<style>
.akzn_2afg {
  cx: 7.25px;
  cy: 11.5px;
  r: 2px;
}

.gplilobog {
  d: path("M2.75 5.5v14.75m0-4.25h18v4.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tdx_tmbvg {
  d: path("M11.75 16v-4.25a1.5 1.5 0 0 1 1.5-1.5h6a1.5 1.5 0 0 1 1.5 1.5V16M16 3.75v4.5M13.75 6h4.5");
}

</style>
