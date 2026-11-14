<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k--li4bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:americano" /></template>
<style>
.k--li4bjo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 9.5h10V19a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2Zm10 2h1a2.5 2.5 0 0 1 0 5h-1M3.5 21h17M9.5 3Q8 4.75 9.5 6.5m4-3.5q-1.5 1.75 0 3.5");
}

</style>
