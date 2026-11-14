<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m65tfqb4d"/><path class="r-cfn2qzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cylinder-shape" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m65tfqb4d {
  d: path("M5.5 5.5c0-1.25 2.75-2.25 6.5-2.25s6.5 1 6.5 2.25v13c0 1.25-2.75 2.25-6.5 2.25s-6.5-1-6.5-2.25Z");
}

.r-cfn2qzg {
  d: path("M5.5 5.5c0 1.25 2.75 2.25 6.5 2.25s6.5-1 6.5-2.25");
}

</style>
