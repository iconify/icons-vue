<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wzdpwmavs"/><path class="f3anvhbxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:io-module" /></template>
<style>
.f3anvhbxq {
  d: path("M8.75 10.25L10.5 12l-1.75 1.75M13.5 12h8m-1.75-1.75L21.5 12l-1.75 1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wzdpwmavs {
  d: path("M9.875 3.5h2.75A4.375 4.375 0 0 1 17 7.875v8.25a4.375 4.375 0 0 1-4.375 4.375h-2.75A4.375 4.375 0 0 1 5.5 16.125v-8.25A4.375 4.375 0 0 1 9.875 3.5M2.5 12h8");
}

</style>
