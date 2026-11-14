<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj5oblbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fit-regular" /></template>
<style>
.pj5oblbbb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3L3 5.75l1.75 4.75L7 9.5V21h10V9.5l2.25 1L21 5.75L15.5 3a3.5 3.5 0 0 1-7 0m1.25 10v2.5m0-1.25h4.5m0-1.25v2.5");
}

</style>
