<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y39g1_ggj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:antenna-off" /></template>
<style>
.y39g1_ggj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3v3.1m0 7.8v2.6M10 3h.01M9 16.5h2a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5H9A2.5 2.5 0 0 1 6.5 19A2.5 2.5 0 0 1 9 16.5m-5.5-13l17 17");
}

</style>
