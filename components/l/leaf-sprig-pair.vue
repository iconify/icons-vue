<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn63etnjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-sprig-pair" /></template>
<style>
.mn63etnjy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 21l8-8m0 0c0-4 3.5-7.5 7.5-7.5c0 4-3.5 7.5-7.5 7.5m-4 4c-3-2-4.5-6.5-3.5-10.5C9 8.5 10.5 13 9 17");
}

</style>
