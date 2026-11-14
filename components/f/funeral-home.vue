<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oea9n_z4j"/><path class="zrir2bcfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:funeral-home" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oea9n_z4j {
  d: path("M5 4h5.5A1.5 1.5 0 0 1 12 5.5v14a1.5 1.5 0 0 1-1.5 1.5H5a1.5 1.5 0 0 1-1.5-1.5v-14A1.5 1.5 0 0 1 5 4m1.25 4.5h3m-3 4h3");
}

.zrir2bcfy {
  d: path("M6.25 21v-4h3v4m7.25-10.75H20c2 2 2 6.25-.25 8.25l.5 2.5h-4l.5-2.5c-2.25-2-2.25-6.25-.25-8.25m-.25-2.75h4");
}

</style>
