<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgaht3b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cocktail-pick" /></template>
<style>
.wgaht3b0f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 20l3.75-3.75m5.5-5.5L18 6M6.75 13.5a3.75 2.75 0 1 0 7.5 0a3.75 2.75 0 1 0-7.5 0M17.5 4.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-7 8.75h.01");
}

</style>
