<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4h05bbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-enrich" /></template>
<style>
.z4h05bbsg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3h12a3.5 3.5 0 0 1 3.5 3.5V7a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 7v-.5A3.5 3.5 0 0 1 6 3m3 0v7.5M15 3v7.5m3 3.75c.25 2.5 1.25 3.5 3.75 3.75c-2.5.25-3.5 1.25-3.75 3.75c-.25-2.5-1.25-3.5-3.75-3.75c2.5-.25 3.5-1.25 3.75-3.75");
}

</style>
