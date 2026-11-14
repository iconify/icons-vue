<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_j-mcc4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crab-whole" /></template>
<style>
.v_j-mcc4x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 14a5.5 3.5 0 1 0 11 0a5.5 3.5 0 1 0-11 0Zm2-2.75L6 8m2-3.5a2.35 2.35 0 1 1-2.5-1m10 7.75L18 8m-2-3.5a2.35 2.35 0 1 0 2.5-1m-12 10l-3.75-1m5.5 4L4 19.5m13.5-6l3.75-1m-5.5 4l4.25 3");
}

</style>
