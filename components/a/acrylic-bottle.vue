<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y7sk0wfyr"/><path class="wr67byrvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:acrylic-bottle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wr67byrvh {
  d: path("M6 14.5q3-1.5 6 0t6 0");
}

.y7sk0wfyr {
  d: path("M9.75 2.5h4.5A1.75 1.75 0 0 1 16 4.25A1.75 1.75 0 0 1 14.25 6h-4.5A1.75 1.75 0 0 1 8 4.25A1.75 1.75 0 0 1 9.75 2.5M9.5 6v1.5C9.5 9 6 9.5 6 12v7.5a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V12c0-2.5-3.5-3-3.5-4.5V6");
}

</style>
