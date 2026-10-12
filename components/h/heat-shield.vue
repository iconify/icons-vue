<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xjdfb-_fd"/><path class="gqquzab7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heat-shield" /></template>
<style>
.gqquzab7v {
  d: path("M10.75 8.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-6.25 11q7.5 3.5 15 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xjdfb-_fd {
  d: path("M10.25 2.75h3.5L20.25 13c0 2.25-3.75 3.5-8.25 3.5S3.75 15.25 3.75 13Z");
}

</style>
