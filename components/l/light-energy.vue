<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-_28ac_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:light-energy" /></template>
<style>
.m-_28ac_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM12 2.5v2.25m0 14.5v2.25M2.5 12h2.25m14.5 0h2.25M6.75 6.75l-1.5-1.5m12 1.5l1.5-1.5m-12 12l-1.5 1.5m12-1.5l1.5 1.5");
}

</style>
