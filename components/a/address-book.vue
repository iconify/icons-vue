<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yx_9c_4fh"/><path class="v5657m7wa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:address-book" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v5657m7wa {
  d: path("M10.75 13.75s-3-2.25-3-5a3 3 0 0 1 6 0c0 2.75-3 5-3 5M3.5 19A2.5 2.5 0 0 1 6 16.5h12");
}

.yx_9c_4fh {
  d: path("M3.5 19V5A2.5 2.5 0 0 1 6 2.5h12v19H6A2.5 2.5 0 0 1 3.5 19M19.375 5.5za1.375 1.375 0 0 1 1.375 1.375v1a1.375 1.375 0 0 1-1.375 1.375A1.375 1.375 0 0 1 18 7.875v-1A1.375 1.375 0 0 1 19.375 5.5m0 6.5za1.375 1.375 0 0 1 1.375 1.375v1a1.375 1.375 0 0 1-1.375 1.375A1.375 1.375 0 0 1 18 14.375v-1A1.375 1.375 0 0 1 19.375 12");
}

</style>
