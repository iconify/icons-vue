<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i15laoiyc"/><path class="tfid_ig9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:laundry-room" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i15laoiyc {
  d: path("M2.5 10h19M5.993 10h12.014a1.75 1.75 0 0 1 1.735 1.976l-1.043 8a1.75 1.75 0 0 1-1.736 1.524H7.037a1.75 1.75 0 0 1-1.736-1.524l-1.043-8A1.75 1.75 0 0 1 5.993 10M6 10c0-3.5 3-5 6-4c2-1.5 5.5-.5 6 4");
}

.tfid_ig9j {
  d: path("M16.375 10h.204a1.5 1.5 0 0 1 1.455 1.136l.936 3.746a1.123 1.123 0 0 1-.845 1.368a1.25 1.25 0 0 1-1.464-.851l-1.257-4.085A1.016 1.016 0 0 1 16.375 10M6 14h8.5m-8 3.75H15");
}

</style>
