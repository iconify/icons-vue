<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bnw_pxbxy"/><path class="odz-e9gkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lip-sync" /></template>
<style>
.bnw_pxbxy {
  d: path("M2.5 9C5 5 7.5 4 9 4.5c1 .25 1.5.75 2 1.25c.5-.5 1-1 2-1.25C14.5 4 17 5 19.5 9C17 14 14 15.5 11 15.5S5 14 2.5 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.odz-e9gkx {
  d: path("M6.5 9.5q4.5-1.5 9 0q-4.5 3.5-9 0m8.75 10.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m3.5 0V15.5m0 0l2.5 1.25");
}

</style>
