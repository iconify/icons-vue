<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z70sz9lfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fire-lay-teepee" /></template>
<style>
.z70sz9lfo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21L13.75 3M21 21L10.25 3M12 2.5v7m0 3.5c2.5 2.5 3 4 3 5a3 3 0 0 1-6 0c0-1 .5-2.5 3-5Z");
}

</style>
