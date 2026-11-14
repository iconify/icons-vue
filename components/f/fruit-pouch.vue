<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m7_42j2ln"/><path class="v0fekyb-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fruit-pouch" /></template>
<style>
.m7_42j2ln {
  d: path("M5 20V10c0-2.25 2.5-4 5-4h4c2.5 0 5 1.75 5 4v10a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 20ZM9.75 2.5h4.5V6h-4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v0fekyb-a {
  d: path("M8.75 15a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM12 11.75l1.75-1.5");
}

</style>
