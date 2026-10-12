<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="irha3emqo"/><path class="u1arpkkvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:enrollment" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.irha3emqo {
  d: path("m12.17 3.58l7.41 3.59q.67.33 0 .66l-7.41 3.59q-.67.33-1.34 0L3.42 7.83q-.67-.33 0-.66l7.41-3.59q.67-.33 1.34 0");
}

.u1arpkkvg {
  d: path("M6.5 9.32v4.18c3 2 7 2 10 0V9.32m2 6.68v5.25m-2.62-2.62h5.25");
}

</style>
