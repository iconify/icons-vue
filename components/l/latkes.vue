<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egljiubos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:latkes" /></template>
<style>
.egljiubos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 9h15v3.75h-15ZM3 12.75h18v3.75H3Zm.75 3.75h16.5v3.75H3.75ZM9 9c0-3 1.75-3 3-5c1.25 2 3 2 3 5");
}

</style>
