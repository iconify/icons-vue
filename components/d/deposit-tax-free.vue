<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="od2p-9noy"/><path class="hdfszv2hq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deposit-tax-free" /></template>
<style>
.hdfszv2hq {
  d: path("M4.5 10.5h-2v3h2m3.25-2.75h.01M10.5 8.5h3m1.5 13l5.75-7.75m-6 .75a1 1 0 1 0 2 0a1 1 0 1 0-2 0M19 20.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0m-4.75-4.5l7.5 3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.od2p-9noy {
  d: path("M12.056 18H12c-.75 0-1.25 0-2-.25v1.75H7.5V17C5.25 16 4 14.25 4 12c0-3.5 3.5-6 8-6c4.1 0 7.369 2.075 7.919 5.091");
}

</style>
