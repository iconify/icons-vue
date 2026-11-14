<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p6ojop6hs"/><path class="r-ih53m4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrow-return-down" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p6ojop6hs {
  d: path("M5.5 15V9.5a4.5 4.5 0 0 1 9 0v10");
}

.r-ih53m4g {
  d: path("m10.5 15.5l4 4l4-4");
}

</style>
