<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2vcmrb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bowling-lane" /></template>
<style>
.s2vcmrb1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 21.5l4-19m15 19l-4-19M7.25 14l1.25-1.5L9.75 14m1-4.5L12 8l1.25 1.5m1 4.5l1.25-1.5l1.25 1.5");
}

</style>
