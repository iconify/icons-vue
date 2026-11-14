<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="awk8bybqw"/><path class="ad_-yzb-z"/><path class="uk6_eqfgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:forex-travel-money" /></template>
<style>
.ad_-yzb-z {
  d: path("M14.25 16a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.awk8bybqw {
  d: path("M6 8h12a3.5 3.5 0 0 1 3.5 3.5V17a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 17v-5.5A3.5 3.5 0 0 1 6 8m2.5 0V5A1.5 1.5 0 0 1 10 3.5h4A1.5 1.5 0 0 1 15.5 5v3m-9 0v12.5M13 8v12.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uk6_eqfgt {
  d: path("M16.25 14h1.25a2 2 0 0 1 0 4h-1.25");
}

</style>
