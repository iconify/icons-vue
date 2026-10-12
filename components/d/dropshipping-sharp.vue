<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgdx8ebvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dropshipping-sharp" /></template>
<style>
.mgdx8ebvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11.25a7.75 7.75 0 0 1 15.5 0M16.25 9l2.25 2.25L20.75 9M6.5 13.75H15v7.5H6.5zm4.25 0v3");
}

</style>
