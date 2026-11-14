<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bcno6qd-g"/><path class="itm8fsbmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-anatomy" /></template>
<style>
.bcno6qd-g {
  d: path("M8 9c-3.5.5-5 4-4.5 7C4 18.5 5 20.5 6 21s3.5-.5 6-1.5c4.5-2 8-5 8-8c0-2.5-2-3.75-4.25-3.25c-1.75.35-3.25 1-4.75 1Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.itm8fsbmq {
  d: path("M11 9.25v-2.5c0-2 1.5-3 3.25-3s3.25 1 3.25 3v1.5m-5-3.75l-.5-2m2.25 1.25V2M16 4l.5-1.75");
}

</style>
