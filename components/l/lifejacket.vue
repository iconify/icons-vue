<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilstnwbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lifejacket" /></template>
<style>
.ilstnwbcx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3c0 3 8 3 8 0l3.5 2v14a2 2 0 0 1-2 2H13V9h-2v12H6.5a2 2 0 0 1-2-2V5ZM4.5 14.5H11m2 0h6.5");
}

</style>
