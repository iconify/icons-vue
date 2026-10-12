<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mucl2eclq"/><path class="enfkylbcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-merge" /></template>
<style>
.enfkylbcb {
  d: path("M8.5 7.5L12 4l3.5 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mucl2eclq {
  d: path("M5.25 20.25L12 13.5m6.75 6.75L12 13.5v-9");
}

</style>
