<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht07h9bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crop-rows" /></template>
<style>
.ht07h9bfw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18.75h1a2.5 2.5 0 0 1 5 0h1a2.5 2.5 0 0 1 5 0h1a2.5 2.5 0 0 1 5 0h1m-17-6.5h1a2 2 0 0 1 4 0h.5a2 2 0 0 1 4 0h.5a2 2 0 0 1 4 0h1M7 6.75h1a1.5 1.5 0 0 1 3 0h2a1.5 1.5 0 0 1 3 0h1");
}

</style>
