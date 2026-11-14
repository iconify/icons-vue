<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lyr3ccqnk"/><path class="m1l7gp4zs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:condenser-mic" /></template>
<style>
.lyr3ccqnk {
  d: path("M10 2.5h4A2.5 2.5 0 0 1 16.5 5v7.5A2.5 2.5 0 0 1 14 15h-4a2.5 2.5 0 0 1-2.5-2.5V5A2.5 2.5 0 0 1 10 2.5Zm2 16v3m-3.5 0h7");
}

.m1l7gp4zs {
  d: path("M4.5 9v1.5a7.5 7.5 0 0 0 15 0V9m-12-.25h9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
