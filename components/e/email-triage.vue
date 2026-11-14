<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e4ndw5b_d"/><path class="pe0z9lbye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:email-triage" /></template>
<style>
.e4ndw5b_d {
  d: path("M13.6 17.5H2.5V4h18v7.9");
}

.pe0z9lbye {
  d: path("m3.5 5.5l8 5.5l8-5.5M15 14.75h6.5L19 18v2.75l-1.5-1V18Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
