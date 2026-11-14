<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpzj5e2su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coat-hanger" /></template>
<style>
.mpzj5e2su {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 6.5a2 2 0 1 1 2 2V11l8.5 6.75a1 1 0 0 1-.5 1.75H4a1 1 0 0 1-.5-1.75L12 11");
}

</style>
