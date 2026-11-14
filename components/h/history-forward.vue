<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sal6b-b0f"/><path class="ix8gp5a6t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:history-forward" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ix8gp5a6t {
  d: path("m16 9l3 3l3-3M11 7.5V12l-3 2");
}

.sal6b-b0f {
  d: path("M15 18.928A8 8 0 1 1 19 12");
}

</style>
