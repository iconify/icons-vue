<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4pox13zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:macaron-sharp" /></template>
<style>
.w4pox13zh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.25c0-2.25 3.8-4 8.5-4s8.5 1.75 8.5 4V10h-17zm1.75.75h13.5v4H5.25zM3.5 14.75V14h17v.75c0 2.25-3.8 4-8.5 4s-8.5-1.75-8.5-4Z");
}

</style>
