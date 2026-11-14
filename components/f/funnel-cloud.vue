<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0e2epb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:funnel-cloud" /></template>
<style>
.h0e2epb7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 9.5a2.5 2.5 0 0 1 0-5H9a3.5 3.5 0 0 1 6 0h3.5a2.5 2.5 0 0 1 0 5Zm3 0c1 4.5 4.5 5.5 5 9c-.5-3.5 1-5.5 2-9M4 21.5h16");
}

</style>
