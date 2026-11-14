<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dd194vuta"/><path class="i-vukufnv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:contract-two-parties" /></template>
<style>
.dd194vuta {
  d: path("M2.5 8.5h4l4-2.5h3L18 9h3.5m-19 5.5h3l5.25 4.5a1.5 1.5 0 0 0 2.25-.5l5.5-4h3m-16.75-6v6M19.25 9v5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-vukufnv {
  d: path("M10.5 6L7.75 9.75A1.5 1.5 0 0 0 10 11l2-1.75");
}

</style>
