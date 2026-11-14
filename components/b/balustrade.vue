<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osh5abe1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:balustrade" /></template>
<style>
.osh5abe1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19m-19 16h19M4.5 4v3c-1.75 2.5-1.75 7.5 0 10v3m0-13c1.75 2.5 1.75 7.5 0 10m5-13v3c-1.75 2.5-1.75 7.5 0 10v3m0-13c1.75 2.5 1.75 7.5 0 10m5-13v3c-1.75 2.5-1.75 7.5 0 10v3m0-13c1.75 2.5 1.75 7.5 0 10m5-13v3c-1.75 2.5-1.75 7.5 0 10v3m0-13c1.75 2.5 1.75 7.5 0 10");
}

</style>
