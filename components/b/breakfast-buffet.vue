<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5u-nnp_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:breakfast-buffet" /></template>
<style>
.y5u-nnp_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 14a8 8 0 0 1 16 0M2.5 14h11.9m5.2 0h1.9M12 6V3.5m2.5 13.25h5v2.75a2 2 0 0 1-2 2h-1a2 2 0 0 1-2-2Zm5 .75a1.25 1.25 0 0 1 0 2.5");
}

</style>
