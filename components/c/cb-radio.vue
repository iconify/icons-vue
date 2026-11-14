<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t0dc5xxvk"/><path class="t5_wswbjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cb-radio" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t0dc5xxvk {
  d: path("M6 9h12a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 6 9m11.5 0L20 3");
}

.t5_wswbjc {
  d: path("M5.5 15a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m9-1.75h4m-4 3.5h4");
}

</style>
