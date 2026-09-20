<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wqyzvvbsm"/><path class="sm7mmswkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cursor-duotone-bold" /></template>
<style>
.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sm7mmswkd {
  d: path("M7 3v15.5l3 -3 3.5 3.5 2.5 -2.5 -3.5 -3.5H17Z");
}

.wqyzvvbsm {
  fill: currentColor;
  d: path("M7 3v15.5l3 -3 3.5 3.5 2.5 -2.5 -3.5 -3.5H17Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
