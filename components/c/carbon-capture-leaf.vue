<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5bsqmnfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:carbon-capture-leaf" /></template>
<style>
.v5bsqmnfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.379 13.653C12.626 16.753 8.395 18.5 3 18.5C3 9 8 3 19 3c0 3.598-.861 6.694-2.474 9.152M3 18.5l8.5-8.5m6.5 4.5v7m-3-3l3 3l3-3");
}

</style>
