<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jpdt6wuay"/><path class="xeqmi2bgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bank-sign" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jpdt6wuay {
  d: path("M3 2.5v7M3 4h17.5M8.625 8.5h8.75A2.625 2.625 0 0 1 20 11.125v7.25A2.625 2.625 0 0 1 17.375 21h-8.75A2.625 2.625 0 0 1 6 18.375v-7.25A2.625 2.625 0 0 1 8.625 8.5M8.5 4v4.5m9-4.5v4.5");
}

.xeqmi2bgb {
  d: path("m11 12.5l1.205-.753a1.5 1.5 0 0 1 1.59 0L15 12.5a.676.676 0 0 1-.358 1.25h-3.284A.676.676 0 0 1 11 12.5m-.75 1.25v3.75M13 13.75v3.75m2.75-3.75v3.75M9 17.5h8");
}

</style>
