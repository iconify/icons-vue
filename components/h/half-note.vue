<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-mn9ybqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:half-note" /></template>
<style>
.i-mn9ybqj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.24 19.12a4 2.9-20 1 0 7.52-2.74a4 2.9-20 1 0-7.52 2.74m7.52-2.74V2.75");
}

</style>
