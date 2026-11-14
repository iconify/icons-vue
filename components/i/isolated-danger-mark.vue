<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="py984hb-m"/><path class="r6-pzkqwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:isolated-danger-mark" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.py984hb-m {
  d: path("M7 14h10l-2 4H9Zm5-3v3m-9 7h18");
}

.r6-pzkqwu {
  fill: currentColor;
  d: path("M10.5 3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
