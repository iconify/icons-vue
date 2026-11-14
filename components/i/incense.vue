<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx3gdi6ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:incense" /></template>
<style>
.kx3gdi6ya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 20.5L14.5 10M4 20.5h16m-4-13c1.5-1.5-1-2.75.5-5m3 7.5c1.5-1.5-1-2.75.5-5");
}

</style>
