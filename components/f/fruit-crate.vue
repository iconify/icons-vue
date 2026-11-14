<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr-n9obdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fruit-crate" /></template>
<style>
.qr-n9obdv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 10h13.75a2.625 2.625 0 0 1 2.625 2.625v5.25a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 17.875v-5.25A2.625 2.625 0 0 1 5.125 10M2.5 15.25h19M2.5 10A3.25 3.25 0 0 1 9 10m0 0a3.25 3.25 0 0 1 6.5 0m0 0a3.25 3.25 0 0 1 6.5 0m-9.75-3.25l1-2.5");
}

</style>
