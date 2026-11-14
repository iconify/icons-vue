<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hma6pr2rz"/><path class="g3xss-p6k"/><path class="wv1490obq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bee-flying" /></template>
<style>
.g3xss-p6k {
  d: path("M8.5 14.75a3.5 4.75 0 1 0 7 0a3.5 4.75 0 1 0-7 0");
}

.hma6pr2rz {
  d: path("M10.5 8.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wv1490obq {
  d: path("M4.75 11.25a2.75 1.75 0 1 0 5.5 0a2.75 1.75 0 1 0-5.5 0m9 0a2.75 1.75 0 1 0 5.5 0a2.75 1.75 0 1 0-5.5 0M11.25 7l-1-1m2.5 1L14 6m-5.25 7.75h6.75M9 16.5h6m-12.5 3c2.5 0 3-3 5.5-3.5");
}

</style>
