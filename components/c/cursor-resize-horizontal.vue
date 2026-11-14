<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ach2qlnqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cursor-resize-horizontal" /></template>
<style>
.ach2qlnqu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.561 10.939l2.878-2.878A.621.621 0 0 1 7.5 8.5A1.5 1.5 0 0 0 9 10h6a1.5 1.5 0 0 0 1.5-1.5a.621.621 0 0 1 1.061-.439l2.878 2.878a1.5 1.5 0 0 1 0 2.122l-2.878 2.878A.621.621 0 0 1 16.5 15.5A1.5 1.5 0 0 0 15 14H9a1.5 1.5 0 0 0-1.5 1.5a.621.621 0 0 1-1.061.439l-2.878-2.878a1.5 1.5 0 0 1 0-2.122");
}

</style>
