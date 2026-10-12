<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugpljcbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:font-family-sharp" /></template>
<style>
.ugpljcbnx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 19.5L8.25 5l4.5 14.5m-7.45-5h5.9m-8.2 5h2.25m6.25 0h2.25M21 11.75v7.75m0-3.75a2.5 3 0 1 1-5 0a2.5 3 0 1 1 5 0");
}

</style>
