<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzap3wo6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dumbbell-heart" /></template>
<style>
.qzap3wo6m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5h4V12H3Zm14 0h4V12h-4ZM7 7.75h10m1 13.75l-2.75-3A2 2 0 0 1 18 15.75a2 2 0 0 1 2.75 2.75Z");
}

</style>
