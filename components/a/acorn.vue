<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6hl1obzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:acorn" /></template>
<style>
.z6hl1obzh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 10c0-4 3.25-5.5 7.5-5.5S19.5 6 19.5 10ZM6 10v2.5c0 4.5 3 7.5 6 9c3-1.5 6-4.5 6-9V10m-6-5.5L13 2");
}

</style>
