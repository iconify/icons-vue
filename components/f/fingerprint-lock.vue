<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pjbn3_b9m"/><path class="uxyplrbvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fingerprint-lock" /></template>
<style>
.pjbn3_b9m {
  d: path("M3 15v-4a7 7 0 0 1 14 0v1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uxyplrbvl {
  d: path("M6.5 18.5V11a3.5 3.5 0 0 1 7 0v1.25M10 20.5V11m5 6h6v4.5h-6Zm1.25 0v-1a1.75 1.75 0 0 1 3.5 0v1");
}

</style>
