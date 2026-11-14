<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygsq-7bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cotton-candy-stick" /></template>
<style>
.ygsq-7bvp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 15a3 3 0 0 1-4.25-3.75a3 3 0 0 1 1.25-5A3.25 3.25 0 0 1 12 4a3.25 3.25 0 0 1 6 2.25a3 3 0 0 1 1.25 5A3 3 0 0 1 15 15a3 3 0 0 1-6 0Zm3 3v3.5");
}

</style>
