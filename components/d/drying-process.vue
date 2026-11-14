<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0818pkwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drying-process" /></template>
<style>
.k0818pkwa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c-1.5 2-4 4-4 6a4 4 0 0 0 8 0c0-2-2.5-4-4-6ZM7 15.25q-1.5 1.5 0 3t0 3m5-6q-1.5 1.5 0 3t0 3m5-6q-1.5 1.5 0 3t0 3");
}

</style>
