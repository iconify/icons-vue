<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="selibsbbx"/><path class="q6l2vr7gn"/><path class="akkgombfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-laundry" /></template>
<style>
.akkgombfb {
  d: path("M11 16.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0M8.5 9h.01m2.99 0h4M7.25 4a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5.25-.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5 .5a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q6l2vr7gn {
  d: path("M8.75 16.25a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M5.5 10.5h13");
}

.selibsbbx {
  d: path("M9 7.5h6a3.5 3.5 0 0 1 3.5 3.5v7a3.5 3.5 0 0 1-3.5 3.5H9A3.5 3.5 0 0 1 5.5 18v-7A3.5 3.5 0 0 1 9 7.5");
}

</style>
