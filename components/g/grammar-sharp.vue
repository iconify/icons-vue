<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgfhowfox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grammar-sharp" /></template>
<style>
.zgfhowfox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.25h18.5m-18.5 5h7.5m3 0h8m-18.5 9h12m-1.5-4.5l1.33-1.25l1.33 1.25l1.33-1.25l1.33 1.25l1.33-1.25l1.33 1.25");
}

</style>
