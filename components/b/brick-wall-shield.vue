<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9vpbkbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brick-wall-shield" /></template>
<style>
.z9vpbkbgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 4.5h13.75A2.625 2.625 0 0 1 21.5 7.125v4.25A2.625 2.625 0 0 1 18.875 14H5.125A2.625 2.625 0 0 1 2.5 11.375v-4.25A2.625 2.625 0 0 1 5.125 4.5M2.5 9.25h19M9 4.5v4.75m6 0V14M6 9.25V14m12 .75L21 16v2.25c0 1.75-1.25 2.75-3 3.5c-1.75-.75-3-1.75-3-3.5V16Z");
}

</style>
