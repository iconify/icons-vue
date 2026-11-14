<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fs-o01b8d"/><path class="vz0cdebun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hydration-level" /></template>
<style>
.fs-o01b8d {
  d: path("M5.5 2.5h13l-1.5 19H7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vz0cdebun {
  d: path("M6 8.5q3-1.5 6 0t6 0M6.25 12h3M6.5 16.5h3");
}

</style>
