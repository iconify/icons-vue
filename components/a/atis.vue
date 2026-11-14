<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azn35e-qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atis" /></template>
<style>
.azn35e-qr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7.5h9v14h-9Zm3 0v-5m0 14h3m5.873-7.91a3.75 3.75 0 0 1 0 4.82m2.298-6.749a6.75 6.75 0 0 1 0 8.678");
}

</style>
