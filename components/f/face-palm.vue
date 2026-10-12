<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ce508fbhh"/><path class="i-g41d1_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-palm" /></template>
<style>
.ce508fbhh {
  d: path("M19.58 16.88A8.75 8.75 0 0 1 12 21.25A8.75 8.75 0 0 1 4.05 8.84");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-g41d1_u {
  d: path("M6.75 13.75h.01m3.24 4c1.25-1 2.75-1 4 0m-5.74-6.41a2 2 0 0 1-.97-2.66l2.12-4.53a1.5 1.5 0 0 1 2.72 1.27l.63-1.36a1.5 1.5 0 0 1 2.72 1.27l.21-.46a1.5 1.5 0 0 1 2.72 1.27l-.42.91a1.5 1.5 0 0 1 2.72 1.27l-2.54 5.43a2 2 0 0 1-2.66.97Zm3.87-5.92l-1.48 3.17m4.83-3.26l-2.11 4.53m4.62-2.81l-1.91 4.08");
}

</style>
