<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pmctwkbox"/><path class="m-500dbxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:contact-reason" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-500dbxc {
  d: path("M14.5 5.25L16.25 7L18 5.25M6.5 16.75H14");
}

.pmctwkbox {
  d: path("M5.625 2.5h12.75A2.625 2.625 0 0 1 21 5.125v1.75A2.625 2.625 0 0 1 18.375 9.5H5.625A2.625 2.625 0 0 1 3 6.875v-1.75A2.625 2.625 0 0 1 5.625 2.5m0 9.75h12.75A2.625 2.625 0 0 1 21 14.875v4a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875v-4a2.625 2.625 0 0 1 2.625-2.625");
}

</style>
