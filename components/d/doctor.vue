<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rknchmb5r"/><path class="bv8m6tbkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:doctor" /></template>
<style>
.bv8m6tbkw {
  d: path("M4 20.25h11a.75.75 0 0 0 .75-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5a.75.75 0 0 0 .75.75M17.65 8h1.2q.4 0 .4.4v.95q0 .4.4.4h.95q.4 0 .4.4v1.2q0 .4-.4.4h-.95q-.4 0-.4.4v.95q0 .4-.4.4h-1.2q-.4 0-.4-.4v-.95q0-.4-.4-.4h-.95q-.4 0-.4-.4v-1.2q0-.4.4-.4h.95q.4 0 .4-.4V8.4q0-.4.4-.4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rknchmb5r {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
}

</style>
