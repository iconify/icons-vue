<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aa_zn31rk"/><path class="gekkhac4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:battery-cell-cylindrical" /></template>
<style>
.aa_zn31rk {
  d: path("M6 7a6 2.25 0 0 1 12 0v11.75a6 2.25 0 0 1-12 0Z");
}

.gekkhac4j {
  d: path("M10.5 5V3h3v2M6 7a6 2.25 0 0 0 12 0M6 11a6 2.25 0 0 0 12 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
