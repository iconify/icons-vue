<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tyvd2kp8c"/><path class="qyvzd5bsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:feed-caught-up" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qyvzd5bsf {
  d: path("m8 12.25l3 3l5.25-5.75");
}

.tyvd2kp8c {
  d: path("M10.25 2.5h3.5A5.25 5.25 0 0 1 19 7.75v8.5a5.25 5.25 0 0 1-5.25 5.25h-3.5A5.25 5.25 0 0 1 5 16.25v-8.5a5.25 5.25 0 0 1 5.25-5.25");
}

</style>
