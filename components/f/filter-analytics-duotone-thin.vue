<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dhloj3obu"/><path class="cvlwadsxk"/><path class="vrfr-0-4l"/><path class="ib0uz7xmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:filter-analytics-duotone-thin" /></template>
<style>
.cvlwadsxk {
  fill: currentColor;
  d: path("M10 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.dhloj3obu {
  fill: currentColor;
  d: path("M3 4h18l-7 7v5h-4v-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ib0uz7xmw {
  d: path("M10 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.vrfr-0-4l {
  d: path("M3 4h18l-7 7v5h-4v-5Z");
}

</style>
