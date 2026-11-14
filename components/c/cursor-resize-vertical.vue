<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0t2i82ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cursor-resize-vertical" /></template>
<style>
.u0t2i82ep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.061 3.561l2.878 2.878A.621.621 0 0 1 15.5 7.5A1.5 1.5 0 0 0 14 9v6a1.5 1.5 0 0 0 1.5 1.5a.621.621 0 0 1 .439 1.061l-2.878 2.878a1.5 1.5 0 0 1-2.122 0l-2.878-2.878A.621.621 0 0 1 8.5 16.5A1.5 1.5 0 0 0 10 15V9a1.5 1.5 0 0 0-1.5-1.5a.621.621 0 0 1-.439-1.061l2.878-2.878a1.5 1.5 0 0 1 2.122 0");
}

</style>
