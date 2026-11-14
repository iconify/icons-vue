<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x0bho7blm"/><path class="tugom2bbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:academic-advisor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tugom2bbj {
  d: path("M7.75 7.75V11a4.25 4.25 0 0 0 8.5 0V7.75M4.5 21.5c0-2 3.25-3.5 7.5-3.5s7.5 1.5 7.5 3.5m1-15.5v4.5");
}

.x0bho7blm {
  d: path("m6.868 4.613l4.561-1.878a1.5 1.5 0 0 1 1.142 0l4.561 1.878a1.5 1.5 0 0 1 0 2.774l-4.561 1.878a1.5 1.5 0 0 1-1.142 0L6.868 7.387a1.5 1.5 0 0 1 0-2.774");
}

</style>
