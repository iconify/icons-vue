<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9l0izn9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:egg-speckled" /></template>
<style>
.h9l0izn9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3c4.5 0 7 6.5 7 11s-3 7-7 7s-7-2.5-7-7S7.5 3 12 3Zm-2 6.5h.01M14.5 13h.01M10 16.5h.01");
}

</style>
