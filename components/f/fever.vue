<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2hekrb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fever" /></template>
<style>
.l2hekrb6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 14V4.5a1.5 1.5 0 0 1 3 0V14a3.5 3.5 0 1 1-3 0ZM10 8.5v7M15 6c1 1.5-1 3 0 4.5M18.5 6c1 1.5-1 3 0 4.5");
}

</style>
