<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hf8qf84mj"/><path class="novfgwbdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chip-lock" /></template>
<style>
.hf8qf84mj {
  d: path("M10 3.5h4A3.5 3.5 0 0 1 17.5 7v10a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 6.5 17V7A3.5 3.5 0 0 1 10 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.novfgwbdi {
  d: path("M14 3.5a2 2 0 0 1-4 0M2.5 8h4m-4 4h4m-4 4h4m11-8h4m-4 4h4m-4 4h4m-10.25-4h1.5a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-1.5a1.5 1.5 0 0 1-1.5-1.5v-.5a1.5 1.5 0 0 1 1.5-1.5m-.5 0v-1a1.25 1.25 0 0 1 2.5 0v1");
}

</style>
