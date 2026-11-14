<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gx9_jwqdm"/><path class="rl5-oib5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:look-to-scroll" /></template>
<style>
.gx9_jwqdm {
  d: path("M3.5 12c2-2.75 5-4 8.5-4s6.5 1.25 8.5 4c-2 2.75-5 4-8.5 4s-6.5-1.25-8.5-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rl5-oib5i {
  d: path("M10.75 12a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M9 5l3-2.5L15 5M9 19l3 2.5l3-2.5");
}

</style>
