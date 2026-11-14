<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c6bmv3q-h"/><path class="sigxgxa6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-bar-negative" /></template>
<style>
.c6bmv3q-h {
  d: path("M2.5 12h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sigxgxa6o {
  fill: currentColor;
  d: path("M4.875 5za.875.875 0 0 1 .875.875v5.25a.875.875 0 0 1-.875.875a.875.875 0 0 1-.875-.875v-5.25A.875.875 0 0 1 4.875 5m5 7za.875.875 0 0 1 .875.875v4.25a.875.875 0 0 1-.875.875a.875.875 0 0 1-.875-.875v-4.25A.875.875 0 0 1 9.875 12m5-9za.875.875 0 0 1 .875.875v7.25a.875.875 0 0 1-.875.875a.875.875 0 0 1-.875-.875v-7.25A.875.875 0 0 1 14.875 3m5 9za.875.875 0 0 1 .875.875v6.25a.875.875 0 0 1-.875.875a.875.875 0 0 1-.875-.875v-6.25a.875.875 0 0 1 .875-.875");
}

</style>
