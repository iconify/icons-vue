<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8zi4tp8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fiber-connector-lc" /></template>
<style>
.f8zi4tp8r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 6h6v10h-6Zm9 0h6v10h-6Zm-9 10h15l-4 3h-7Zm7.5 3v2.5M7.5 6V3m9 3V3");
}

</style>
