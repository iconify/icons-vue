<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lxuv62kcy"/><path class="e7maqcb0g"/><path class="olo9et2dz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:api-analytics" /></template>
<style>
.e7maqcb0g {
  d: path("M2.5 7L7 2.5h14.5V17L17 21.5M17 7l4.5-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lxuv62kcy {
  d: path("M4 7h11.5A1.5 1.5 0 0 1 17 8.5V20a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 20V8.5A1.5 1.5 0 0 1 4 7");
}

.olo9et2dz {
  d: path("m5.5 17.5l3-4l2.5 2l3-5");
}

</style>
