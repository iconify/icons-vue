<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-m5upsap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bill-rejected" /></template>
<style>
.e-m5upsap {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h14V21l-2.25-1.5L14.5 21L12 19.5L9.5 21l-2.25-1.5L5 21ZM9 8l6 6m0-6l-6 6");
}

</style>
