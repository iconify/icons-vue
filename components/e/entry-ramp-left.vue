<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s2q29qqkn"/><path class="h3-8vi6zb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:entry-ramp-left" /></template>
<style>
.h3-8vi6zb {
  d: path("M9.75 5.25L7 8l2.75 2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s2q29qqkn {
  d: path("M17 21.5v-19M17 17c0-6-5-9-10-9");
}

</style>
