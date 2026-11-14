<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t2nubf2he"/><path class="mo5347bwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-in-cot-hospital" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mo5347bwd {
  d: path("M6.25 8.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m5.25 0h6m-10 4l9 6.5m0-6.5l-9 6.5m-1.75 1.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m10 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.t2nubf2he {
  d: path("M6.5 4.5h11A3.5 3.5 0 0 1 21 8v1a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 9V8a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
