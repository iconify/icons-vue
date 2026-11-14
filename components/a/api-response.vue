<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wpumxvbbr"/><path class="xc_unvbvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:api-response" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wpumxvbbr {
  d: path("M7.75 4.5L13 7.25v9.5L7.75 19.5L2.5 16.75v-9.5Z");
}

.xc_unvbvr {
  d: path("M2.5 7.25L7.75 10L13 7.25M7.75 10v9.5M21.5 12h-5.75m2.75-2.75L15.75 12l2.75 2.75");
}

</style>
