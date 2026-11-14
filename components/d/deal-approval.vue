<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wlvt70rhh"/><path class="dqivb5cea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deal-approval" /></template>
<style>
.dqivb5cea {
  d: path("m3.738 19.272l.833-1.5A1.5 1.5 0 0 1 5.883 17h13.068a1.5 1.5 0 0 1 1.311 2.228l-.833 1.5a1.5 1.5 0 0 1-1.312.772H5.049a1.5 1.5 0 0 1-1.311-2.228M10.5 8.5V13m3-4.5V13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wlvt70rhh {
  d: path("M9 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-1.25 7h8.5A1.75 1.75 0 0 1 18 14.75v.5A1.75 1.75 0 0 1 16.25 17h-8.5A1.75 1.75 0 0 1 6 15.25v-.5A1.75 1.75 0 0 1 7.75 13");
}

</style>
