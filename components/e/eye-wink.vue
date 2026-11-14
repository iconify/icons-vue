<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o9-hdx-mj"/><path class="h62x9kblw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eye-wink" /></template>
<style>
.h62x9kblw {
  d: path("M5.5 12A1.25 1.25 0 1 0 8 12a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o9-hdx-mj {
  d: path("M2.5 12C3.75 9.5 5 8 6.75 8s3 1.5 4.25 4c-1.25 2.5-2.5 4-4.25 4s-3-1.5-4.25-4m11.25-1q4 5.5 7.75 0");
}

</style>
