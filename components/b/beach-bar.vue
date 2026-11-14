<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyd4_ybby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beach-bar" /></template>
<style>
.fyd4_ybby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 6.5l4-4h10l4 4L18.75 8L16.5 6.5L14.25 8L12 6.5L9.75 8L7.5 6.5L5.25 8ZM5.25 8v7m13.5-7v7M3 15h18v6H3Zm6.5-4h5L12 13.75Zm2.5 2.75V15");
}

</style>
