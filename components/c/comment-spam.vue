<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m69eo45wu"/><path class="qz8s4pifk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:comment-spam" /></template>
<style>
.m69eo45wu {
  d: path("M5 17a8.5 8.5 0 1 1 15.5-4.75h-6.25a2 2 0 0 0-2 2v6.25a8.5 8.5 0 0 1-4.75-1l-3.5 1Z");
}

.qz8s4pifk {
  d: path("M15 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm1-2l4 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
