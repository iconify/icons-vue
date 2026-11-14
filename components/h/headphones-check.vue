<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi62t9cwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:headphones-check" /></template>
<style>
.pi62t9cwo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13.5v-1a7 7 0 0 1 14 0v1m-13.5 0zA2.5 2.5 0 0 1 8 16v2a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 3 18v-2a2.5 2.5 0 0 1 2.5-2.5m13 0zA2.5 2.5 0 0 1 21 16v2a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 16 18v-2a2.5 2.5 0 0 1 2.5-2.5M10 16l1.5 1.5L14 15");
}

</style>
