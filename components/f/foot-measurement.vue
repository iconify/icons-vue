<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dekez9v6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:foot-measurement" /></template>
<style>
.dekez9v6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6.5c3.5 0 4.5 3 4 6C12 15 11 16 11 18s-.5 3.5-2.5 3.5s-3-1.5-2.5-4S4 13 4 10c0-2 2-3.5 4.5-3.5ZM4.5 4h.01M8 3h.01m3.49 1h.01m3.99 14v3h3m-3 0l5.5-5.5m-3 0h3v3");
}

</style>
