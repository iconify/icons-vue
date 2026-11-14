<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c6bmv3q-h"/><path class="ezos9f31h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-win-loss" /></template>
<style>
.c6bmv3q-h {
  d: path("M2.5 12h19");
}

.ezos9f31h {
  fill: currentColor;
  d: path("M4 5za1 1 0 0 1 1 1v3a1 1 0 0 1-1 1a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1m3.5 0za1 1 0 0 1 1 1v3a1 1 0 0 1-1 1a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1m3.5 9za1 1 0 0 1 1 1v3a1 1 0 0 1-1 1a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1m3.5-9za1 1 0 0 1 1 1v3a1 1 0 0 1-1 1a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1m3.5 9za1 1 0 0 1 1 1v3a1 1 0 0 1-1 1a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1m2.875 0za.875.875 0 0 1 .875.875v3.25a.875.875 0 0 1-.875.875a.875.875 0 0 1-.875-.875v-3.25a.875.875 0 0 1 .875-.875");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
