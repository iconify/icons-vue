<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0857_b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cable" /></template>
<style>
.i0857_b0i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.625 6h2.75A2.625 2.625 0 0 1 16 8.625v.75A2.625 2.625 0 0 1 13.375 12h-2.75A2.625 2.625 0 0 1 8 9.375v-.75A2.625 2.625 0 0 1 10.625 6M10 2.5V6m4-3.5V6m-2 6c0 3.5-7.5 2.5-7.5 6s10.5 3.5 15-.5");
}

</style>
