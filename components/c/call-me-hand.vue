<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msxbre13q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:call-me-hand" /></template>
<style>
.msxbre13q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.01 4.97L9.7 8.41q.46.59 1.21.59H14q2 0 2 2v3.39q0 .75.56 1.25l2.09 1.85q.93.83.1 1.76t-1.76.1L14.9 17.5q-.56-.5-1.31-.5H10q-2 0-2-2v-3.95q0-.75-.46-1.34L5.03 6.5q-.77-.98.22-1.75t1.76.22M10.25 13h4.5M9.25 3c.9.2 1.7.7 2.25 1.5M2.75 8.75c.2.9.7 1.7 1.5 2.25");
}

</style>
