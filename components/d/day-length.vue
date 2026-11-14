<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frhv-l2wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:day-length" /></template>
<style>
.frhv-l2wr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11a6.5 6.5 0 0 1 13 0m-16 0h19M4 17h16M6.5 14.5L4 17l2.5 2.5m11-5L20 17l-2.5 2.5");
}

</style>
