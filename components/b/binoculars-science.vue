<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uza2veb8u"/><path class="pxg8vub9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:binoculars-science" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pxg8vub9l {
  d: path("M2.5 15.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m11 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0m-3-6.5h3");
}

.uza2veb8u {
  d: path("M2.5 15.5V7a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v8.5m3 0V7a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v8.5");
}

</style>
