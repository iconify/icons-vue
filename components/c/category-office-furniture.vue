<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdpozsbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-office-furniture" /></template>
<style>
.xdpozsbql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.25h9v9.5h-9Zm-2.5 11h14V16H4Zm7-1.5v1.5M11 16v2.5m0 0l-8.5 1m8.5-1L6.5 21m4.5-2.5v3m0-3l4.5 2.5M11 18.5l8.5 1M18 13.25V9.5h2.5m-18 10h.01M6.5 21h.01m4.49.5h.01m4.49-.5h.01m3.99-1.5h.01");
}

</style>
