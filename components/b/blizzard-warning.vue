<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usd9mxtrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blizzard-warning" /></template>
<style>
.usd9mxtrs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12a3 3 0 0 1 0-6a4.25 4.25 0 0 1 8.25.75A2.75 2.75 0 0 1 13 12Zm0 3.5h.01m3.99 0h.01m3.99 0h.01m-6.01 4h.01m3.99 0h.01M20 4v10m0 4.25h.01");
}

</style>
