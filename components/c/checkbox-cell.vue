<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a95ub6bhf"/><path class="jjcj9_b4d"/><path class="qq2d4c65n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:checkbox-cell" /></template>
<style>
.a95ub6bhf {
  d: path("M6 4.5h12A3.5 3.5 0 0 1 21.5 8v8a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 16V8A3.5 3.5 0 0 1 6 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jjcj9_b4d {
  d: path("M8.125 7.5h3.75a2.625 2.625 0 0 1 2.625 2.625v3.75a2.625 2.625 0 0 1-2.625 2.625h-3.75A2.625 2.625 0 0 1 5.5 13.875v-3.75A2.625 2.625 0 0 1 8.125 7.5");
}

.qq2d4c65n {
  d: path("m7.5 12l1.75 1.75l3.25-3.5m5 1.75h1");
}

</style>
