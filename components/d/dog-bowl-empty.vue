<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sq137tf4g"/><path class="qrxxeacvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dog-bowl-empty" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qrxxeacvm {
  d: path("M3 8.5L5.25 17q.5 1.5 2 1.5h9.5q1.5 0 2-1.5L21 8.5");
}

.sq137tf4g {
  d: path("M3 8.5a9 2.5 0 1 0 18 0a9 2.5 0 1 0-18 0");
}

</style>
