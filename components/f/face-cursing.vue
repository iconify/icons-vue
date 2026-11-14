<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mcdmdujpa"/><path class="ld4r858hn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:face-cursing" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ld4r858hn {
  d: path("m7.5 17.5l2.25-2l2.25 2l2.25-2l2.25 2");
}

.mcdmdujpa {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0m4.25-4.25l3.5 1.5m7-1.5l-3.5 1.5M9 12h.01M15 12h.01");
}

</style>
