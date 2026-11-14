<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="thtewvqgi"/><path class="xx2q2z9nb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:alloy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.thtewvqgi {
  d: path("m3.216 16.995l1.428-4A1.5 1.5 0 0 1 6.057 12h5.886a1.5 1.5 0 0 1 1.413.995l1.428 4A1.5 1.5 0 0 1 13.371 19H4.629a1.5 1.5 0 0 1-1.413-2.005");
}

.xx2q2z9nb {
  d: path("m9.5 12l2.25-6.5H19l2.5 8.5h-7.75M6.5 15.5c.75-1.25 1.75-1.25 2.5 0s1.75 1.25 2.5 0");
}

</style>
