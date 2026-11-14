<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wd960cx7t"/><path class="gor9o5bgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crosswalk-kids" /></template>
<style>
.gor9o5bgp {
  d: path("M10 13.75v1.75L8.5 18m1.5-2.5l1.5 2.5m3.5-4.5h.01M15 15.75v.5L14 18m1-1.75L16 18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wd960cx7t {
  d: path("m14.307 7.25l5.088 9.373a2.625 2.625 0 0 1-2.307 3.877H6.912a2.625 2.625 0 0 1-2.307-3.877L9.693 7.25a2.625 2.625 0 0 1 4.614 0M10 11h.01");
}

</style>
