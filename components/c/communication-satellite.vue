<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="taacos_vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:communication-satellite" /></template>
<style>
.taacos_vr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8.5a7.5 7.5 0 0 0 10 10Zm5 5L13 11m-6 6l-2.25 2.25M3 17.5L6.5 21M13 7.5a3.5 3.5 0 0 1 3.5 3.5M13 4.5a6.5 6.5 0 0 1 6.5 6.5");
}

</style>
