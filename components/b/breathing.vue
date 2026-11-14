<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqik3_bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:breathing" /></template>
<style>
.hqik3_bko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 8.5c-2.5-2-6.5.5-6.5 6c0 3.25 1 5.5 3.25 5.5S10 18.75 10 16.5Zm4 0c2.5-2 6.5.5 6.5 6c0 3.25-1 5.5-3.25 5.5S14 18.75 14 16.5ZM12 3v7");
}

</style>
