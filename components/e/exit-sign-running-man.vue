<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn7tnnbwb"/><path class="m2ce8yk9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:exit-sign-running-man" /></template>
<style>
.hn7tnnbwb {
  d: path("M2.5 5h19v14h-19Z");
}

.m2ce8yk9l {
  d: path("M14.5 16V9h4v7m-7.75-8.25h.01M9.75 10.5l-1.5 3l2 2.5m-2-2.5L6 16m.5-4.75l3.25-.75l2 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
