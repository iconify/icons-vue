<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8bia3bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:case-upper-sharp" /></template>
<style>
.h8bia3bbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 19.25l4-14.5l4 14.5m-6.6-5h5.2m4.15-9.5v14.5m0-14.5h3.5a3.5 3.5 0 0 1 0 7h-3.5m0 0h3.75a3.75 3.75 0 0 1 0 7.5h-3.75");
}

</style>
