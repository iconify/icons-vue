<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfx4_jbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:director-viewfinder" /></template>
<style>
.cfx4_jbjk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8V5.5A2.5 2.5 0 0 1 5.5 3H8m8 0h2.5A2.5 2.5 0 0 1 21 5.5V8m0 8v2.5a2.5 2.5 0 0 1-2.5 2.5H16m-8 0H5.5A2.5 2.5 0 0 1 3 18.5V16m5.5-4a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
