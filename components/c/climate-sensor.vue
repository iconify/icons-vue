<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dqslx2bti"/><path class="u84joidvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:climate-sensor" /></template>
<style>
.dqslx2bti {
  d: path("M9.75 2.5h4.5a5.25 5.25 0 0 1 5.25 5.25v8.5a5.25 5.25 0 0 1-5.25 5.25h-4.5a5.25 5.25 0 0 1-5.25-5.25v-8.5A5.25 5.25 0 0 1 9.75 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u84joidvd {
  d: path("M10.5 13V8a1.5 1.5 0 0 1 3 0v5a3 3 0 1 1-3 0");
}

</style>
