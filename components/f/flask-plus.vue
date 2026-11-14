<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfx9b0bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flask-plus" /></template>
<style>
.jfx9b0bec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3.5V9l-5 9.5q-1 2 1.25 2h5.931m3.513-8.28L14 9V3.5m-5.5 0h7M18 15v6m-3-3h6");
}

</style>
