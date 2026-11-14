<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yyl5_z67i"/><path class="d31w4ybng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:alzheimers" /></template>
<style>
.d31w4ybng {
  d: path("M4.25 10.5c2.25-1 4.75.25 7-1.25M10.5 3c-.5 1.75.5 3 0 4.5m3 4c.75-.75 2-.5 2.5-1.5m-1.25 6.25h2c0-1.5 2.5-1.5 2.5 0h2v2c-1.5 0-1.5 2 0 2v1.5h-6.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yyl5_z67i {
  d: path("M12.514 14.554c-.833.227-1.797.126-2.514-.304c-1.25.75-3.25.5-4-.75c-1.75.25-3-1.25-2.75-2.75c-1-1-1-3 .25-3.75c0-1.5 1.25-2.25 2.5-2c.5-1.5 2.25-2.25 4-1.75c1-1 3-.75 4 .5c1.75 0 3 1.25 2.75 3c1.25 1 1.25 3 .25 4c0 .67-.183 1.267-.508 1.734m-2.17 1.046A3 3 0 0 1 14 13.5l-.066.102");
}

</style>
