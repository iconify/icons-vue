<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1m9g0bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:battery-heating" /></template>
<style>
.g1m9g0bnw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h16v9H3Zm16 2.75h1.5v3.5H19M7 8Q6 6.875 7 5.75T7 3.5M11 8q-1-1.125 0-2.25t0-2.25M15 8q-1-1.125 0-2.25t0-2.25");
}

</style>
