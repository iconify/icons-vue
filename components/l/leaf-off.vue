<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1ek-yp8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-off" /></template>
<style>
.m1ek-yp8x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.298 17.236C10.946 18.731 8.084 19.386 5 19c-.394-3.155.144-6.076 1.586-8.458m3.998-3.907C12.881 5.281 15.86 4.5 19.5 4.5c0 3.404-.834 6.358-2.273 8.702M3 21l7-7M3.5 3.5l17 17");
}

</style>
