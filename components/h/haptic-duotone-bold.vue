<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x_i-jbbeq"/><path class="oayjtvtuh"/><path class="yxwimoiqt"/><path class="klj1k5byh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:haptic-duotone-bold" /></template>
<style>
.klj1k5byh {
  d: path("M4.17 14.83a4 4 0 0 1 0 -5.66");
}

.oayjtvtuh {
  d: path("M8 5a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x_i-jbbeq {
  fill: currentColor;
  d: path("M8 5a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yxwimoiqt {
  d: path("M19.83 9.17a4 4 0 0 1 0 5.66");
}

</style>
