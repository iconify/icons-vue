<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvznz-bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-collapse-all" /></template>
<style>
.nvznz-bmw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6.5L12 3l5 3.5M7 10l5-3.5l5 3.5m-8.5 3.5l-4 3.75l4 3.75m7-7.5l4 3.75l-4 3.75");
}

</style>
