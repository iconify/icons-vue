<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a95ub6bhf"/><path class="e-t8v6zbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:banknote-taka" /></template>
<style>
.a95ub6bhf {
  d: path("M6 4.5h12A3.5 3.5 0 0 1 21.5 8v8a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 16V8A3.5 3.5 0 0 1 6 4.5");
}

.e-t8v6zbb {
  d: path("M8.75 8.5c-.05-.7.5-1.15 1-1c.6.15.75.75.75 1.5v5c0 1.45 1.05 2.5 2.5 2.5c1.25 0 2.3-1.05 2.25-2.5c.05-1.1-.7-1.85-1.5-1.75m-5-1.75h3.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
