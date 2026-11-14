<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hzy4vlbdd"/><path class="m5hmsrcrk"/><path class="ctoc2ibvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:engagement-ring-box" /></template>
<style>
.ctoc2ibvt {
  d: path("M10 6.5h4l-2 2Z");
}

.hzy4vlbdd {
  d: path("M3 13.5h18V21H3Zm1 0L5 3h14l1 10.5");
}

.m5hmsrcrk {
  d: path("M9.5 11a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
