<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc42e_w8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:build-failed" /></template>
<style>
.uc42e_w8d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.413 21.189L3.5 17V7L12 2.5L20.5 7v5.082M3.5 7l8.5 4.5M20.5 7L12 11.5m0 0v2.6m0 1.8v4.7m3-5.6l6.5 6.5m0-6.5L15 21.5");
}

</style>
