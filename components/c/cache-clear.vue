<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0f92cuau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cache-clear" /></template>
<style>
.k0f92cuau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11 3l8 4l-8 4l-8-4Zm-8 8l8 4l2.196-1.098m3.131-1.565L19 11M3 15l8 4l2.5-1.25m2-2.25l5 5m0-5l-5 5");
}

</style>
