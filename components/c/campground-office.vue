<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p8-8vpgvt"/><path class="a476ddbkp"/><path class="isj115b3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campground-office" /></template>
<style>
.a476ddbkp {
  d: path("M7.5 11.25h9l1.5 2.5q-2 2-4 0q-2 2-4 0q-2 2-4 0Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.isj115b3t {
  d: path("M6 13.75V18h12v-4.25");
}

.p8-8vpgvt {
  d: path("m3.434 9.713l6.875-5.789a2.625 2.625 0 0 1 3.382 0l6.875 5.789a2.63 2.63 0 0 1 .934 2.008v6.654A2.625 2.625 0 0 1 18.875 21H5.125A2.625 2.625 0 0 1 2.5 18.375v-6.654a2.63 2.63 0 0 1 .934-2.008");
}

</style>
