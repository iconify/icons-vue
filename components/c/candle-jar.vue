<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bmj9enste"/><path class="as_rb7_zl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:candle-jar" /></template>
<style>
.as_rb7_zl {
  d: path("M9.5 13.5h5A1.5 1.5 0 0 1 16 15v1a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 8 16v-1a1.5 1.5 0 0 1 1.5-1.5");
}

.bmj9enste {
  d: path("M9.375 9.75h5.25A4.375 4.375 0 0 1 19 14.125v3a4.375 4.375 0 0 1-4.375 4.375h-5.25A4.375 4.375 0 0 1 5 17.125v-3A4.375 4.375 0 0 1 9.375 9.75M12 2.5c1.5 1.5 1.75 2.25 1.75 2.75a1.75 1.75 0 0 1-3.5 0c0-.5.25-1.25 1.75-2.75M12 7v2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
