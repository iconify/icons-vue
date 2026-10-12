<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6xvawe5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flag-checkered-sharp" /></template>
<style>
.w6xvawe5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4h7.5v4.5H5zm7.5 4.5H20V13h-7.5zm0-4.5H20v4.5M5 13h7.5M5 3v1m0 4.5V21");
}

</style>
