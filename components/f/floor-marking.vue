<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrqar-dtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:floor-marking" /></template>
<style>
.vrqar-dtz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.326 4h7.348a1.75 1.75 0 0 1 1.685 1.276l3.516 12.5A1.75 1.75 0 0 1 19.19 20H4.81a1.75 1.75 0 0 1-1.685-2.224l3.516-12.5A1.75 1.75 0 0 1 8.326 4M10 7L8 17m6-10l2 10");
}

</style>
