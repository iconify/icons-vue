<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm2ihncej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:font-family" /></template>
<style>
.lm2ihncej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5L7.25 4L12 20.5m-7.75-6h6m4 2.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m7-4.5v8");
}

</style>
