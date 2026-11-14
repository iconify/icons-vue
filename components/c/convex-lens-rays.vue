<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qpbs895_q"/><path class="ev2a68btr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:convex-lens-rays" /></template>
<style>
.ev2a68btr {
  d: path("M3.5 7.5h5l12 4.5m-17 4.5h5l12-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qpbs895_q {
  d: path("M8.5 3q4 9 0 18q-4-9 0-18");
}

</style>
