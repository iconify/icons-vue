<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y3rmcvael"/><rect class="kjckrwb_y"/><path class="yhv3clb8j"/><circle class="osg1l5s9n"/><circle class="p9owqpkmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gurney" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kjckrwb_y {
  width: 18.5px;
  height: 3.5px;
  x: 2.75px;
  y: 8.75px;
  rx: 1.5px;
}

.osg1l5s9n {
  cx: 8px;
  cy: 19.5px;
  r: 1.5px;
}

.p9owqpkmi {
  cx: 16px;
  cy: 19.5px;
  r: 1.5px;
}

.y3rmcvael {
  d: path("M4.5 8.75V7.5a1.25 1.25 0 0 1 1.25-1.25h3A1.25 1.25 0 0 1 10 7.5v1.25Z");
}

.yhv3clb8j {
  d: path("M8 12.25L16 18m0-5.75L8 18");
}

</style>
