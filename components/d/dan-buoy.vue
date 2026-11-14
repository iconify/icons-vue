<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk3r_oq0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dan-buoy" /></template>
<style>
.rk3r_oq0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 18a6 3.5 0 1 0 12 0a6 3.5 0 1 0-12 0Zm6-15.5v12m0-12L18.5 5L12 7.5Z");
}

</style>
