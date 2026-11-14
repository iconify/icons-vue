<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qmptz25oz"/><path class="wt6qa4bxu"/><path class="jmwtvgb0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:house-door-open" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jmwtvgb0y {
  d: path("m13.909 12.11l.841-.36a1.255 1.255 0 0 1 1.75 1.154v3.357a1.5 1.5 0 0 1-.909 1.379l-.841.36A1.255 1.255 0 0 1 13 16.846v-3.357a1.5 1.5 0 0 1 .909-1.379");
}

.qmptz25oz {
  d: path("m4.422 9.714l5.875-5.011a2.625 2.625 0 0 1 3.406 0l5.875 5.011a2.63 2.63 0 0 1 .922 1.997v6.164a2.625 2.625 0 0 1-2.625 2.625H6.125A2.625 2.625 0 0 1 3.5 17.875v-6.164a2.63 2.63 0 0 1 .922-1.997");
}

.wt6qa4bxu {
  d: path("M7.5 20.5v-8H13v8");
}

</style>
