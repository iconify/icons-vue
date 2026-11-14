<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4lxxtbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flag-cross" /></template>
<style>
.g4lxxtbcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5v19m0-18h12.5A1.5 1.5 0 0 1 19 5v7a1.5 1.5 0 0 1-1.5 1.5H5m7-7.25v4.5M9.25 8.5h5.5");
}

</style>
