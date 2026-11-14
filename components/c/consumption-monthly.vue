<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ubifyzbew"/><path class="z41qhfbtb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:consumption-monthly" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ubifyzbew {
  d: path("M3.5 3v17.5h7.7");
}

.z41qhfbtb {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5M16.188 15h3.625A2.19 2.19 0 0 1 22 17.188v2.625A2.19 2.19 0 0 1 19.813 22h-3.625A2.19 2.19 0 0 1 14 19.813v-2.625A2.19 2.19 0 0 1 16.188 15M14 18h8m-5.5-4.75v3m3-3v3");
}

</style>
