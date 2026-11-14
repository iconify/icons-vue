<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yw-i7lbri"/><path class="rhpulgbdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forecast-accuracy" /></template>
<style>
.rhpulgbdw {
  d: path("M6.75 13a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0ZM11 13l8-8m0-2.5V5h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yw-i7lbri {
  d: path("M2.5 13a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0Z");
}

</style>
