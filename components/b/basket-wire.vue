<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu5c-q3zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basket-wire" /></template>
<style>
.mu5c-q3zt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10h18l-2 10H5Zm4.5 0V8.5a4.5 4.5 0 0 1 9 0V10m-8 3v4m3.5-4v4m3.5-4v4");
}

</style>
