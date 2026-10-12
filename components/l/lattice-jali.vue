<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="izuxxacqb"/><path class="brkx4hmly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lattice-jali" /></template>
<style>
.brkx4hmly {
  d: path("m9 11.25l1.5 1.5l-1.5 1.5l-1.5-1.5Zm6 0l1.5 1.5l-1.5 1.5l-1.5-1.5Zm-6 5l1.5 1.5l-1.5 1.5l-1.5-1.5Zm6 0l1.5 1.5l-1.5 1.5l-1.5-1.5ZM12 5.5l1 1.25L12 8l-1-1.25Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.izuxxacqb {
  d: path("M5 10a7 7 0 0 1 14 0v10a1.25 1.25 0 0 1-1.25 1.25H6.25A1.25 1.25 0 0 1 5 20Z");
}

</style>
