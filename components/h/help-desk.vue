<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euu6f_y5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:help-desk" /></template>
<style>
.euu6f_y5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 12.25v-2a7.5 7.5 0 0 1 15 0v2m-16.5 0h4v6H3Zm14 0h4v6h-4Zm2 6v.5a2.5 2.5 0 0 1-2.5 2.5H13");
}

</style>
