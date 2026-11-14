<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tr78iebwu"/><path class="cyayf_7wz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:city-hall" /></template>
<style>
.cyayf_7wz {
  d: path("M10 21v-3.5a2 2 0 0 1 4 0V21m-8-6.5v3m12-3v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tr78iebwu {
  d: path("M3 21v-9.5h5.5V6L12 2.75L15.5 6v5.5H21V21M2.5 21h19");
}

</style>
