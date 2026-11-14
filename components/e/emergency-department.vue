<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i8v446zyh"/><path class="hj28stbge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:emergency-department" /></template>
<style>
.hj28stbge {
  d: path("M9.5 21.5V16h5v5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i8v446zyh {
  d: path("M5.625 9.5h12.75A2.625 2.625 0 0 1 21 12.125v6.75a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875v-6.75A2.625 2.625 0 0 1 5.625 9.5M10 8V6c0-1.1.9-2 2-2s2 .9 2 2v2M9 8h6M7.5 4.5l1 1m8-1l-1 1m-10 8h13");
}

</style>
