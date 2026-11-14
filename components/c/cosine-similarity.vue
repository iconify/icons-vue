<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y__7gtbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cosine-similarity" /></template>
<style>
.y__7gtbek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 17.5h17M18 15l2.5 2.5L18 20M3.5 17.5l13-13m-3.5 0h3.5V8m-8.05 4.55a7 7 0 0 1 2.05 4.95");
}

</style>
