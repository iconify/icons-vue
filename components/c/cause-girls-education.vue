<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uubapyjaf"/><path class="bxf3edcfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cause-girls-education" /></template>
<style>
.bxf3edcfr {
  d: path("M7.5 7v3c2.5 1.5 6.5 1.5 9 0V7M12 14.5v7.25M20.5 5.5V10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uubapyjaf {
  d: path("M12 14.5q-3-1.5-9-.75V21q6-.75 9 .75q3-1.5 9-.75v-7.25q-6-.75-9 .75M7.75 4l3.668-1.294a1.75 1.75 0 0 1 1.164 0L16.25 4a1.591 1.591 0 0 1 0 3l-3.668 1.294a1.75 1.75 0 0 1-1.164 0L7.75 7a1.591 1.591 0 0 1 0-3");
}

</style>
