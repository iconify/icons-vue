<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-3y-4brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:defendant" /></template>
<style>
.n-3y-4brw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 7a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0ZM2.5 21c0-4 3-6.5 6.5-6.5c2.069 0 3.963.874 5.166 2.414m3.95-3.566l3.536 3.536l-1.768 1.768l-3.536-3.536ZM18 17l-3.25 3.25");
}

</style>
