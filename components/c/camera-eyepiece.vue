<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f8xw6t5jm"/><path class="uu0i74b4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-eyepiece" /></template>
<style>
.f8xw6t5jm {
  d: path("M5.5 3.5h4M6.875 6.25h4.25a4.375 4.375 0 0 1 4.375 4.375v4.75a4.375 4.375 0 0 1-4.375 4.375h-4.25A4.375 4.375 0 0 1 2.5 15.375v-4.75A4.375 4.375 0 0 1 6.875 6.25M15.5 8.5h2v4h-2m4-6za2 2 0 0 1 2 2v4a2 2 0 0 1-2 2a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uu0i74b4c {
  d: path("M6 13a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
