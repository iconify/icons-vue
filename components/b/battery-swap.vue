<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="y6nr_abgb"/><path class="vdxf26b1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:battery-swap" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vdxf26b1d {
  d: path("M21.25 10.5v3M6 10v4m3.25-4v4m3.25-4v4m3.25-4v4");
}

.y6nr_abgb {
  width: 16px;
  height: 10.5px;
  x: 2.75px;
  y: 6.75px;
  rx: 2.5px;
}

</style>
