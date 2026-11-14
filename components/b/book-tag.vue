<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oe5rf_bvb"/><path class="hx9vpzbld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:book-tag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hx9vpzbld {
  d: path("M2.5 19A2.5 2.5 0 0 1 5 16.5h8.5m0-10.5l5.75 3l2.5 3v8.5H16.5V12l2.75-3m0 4.25h.01");
}

.oe5rf_bvb {
  d: path("M2.5 19V5A2.5 2.5 0 0 1 5 2.5h8.5v19H5A2.5 2.5 0 0 1 2.5 19");
}

</style>
