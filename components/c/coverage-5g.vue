<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="dix6q076p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coverage-5g" /></template>
<style>
.dix6q076p {
  d: path("M10.5 8.5H7.25L7 11.75c.5-.25 1-.5 1.75-.5c1.25 0 2 1 2 2.25s-.75 2-2 2c-.75 0-1.25-.25-1.75-.75M17.25 9.5c-.25-.75-1-1-1.75-1c-1.5 0-2 1.5-2 3.5s.5 3.5 2 3.5c1.25 0 2-1 2-2.5v-.5h-1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
