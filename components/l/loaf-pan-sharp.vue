<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2c107bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:loaf-pan-sharp" /></template>
<style>
.z2c107bko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 11c0-3.5 3-5.75 7-5.75S19 7.5 19 11Zm0 0h15.25l-.2 1.23l-1.1 6.79l-.2 1.23H5.25l-.2-1.23l-1.1-6.79l-.2-1.23zm-1.25 0h-1m17.5 0h1");
}

</style>
