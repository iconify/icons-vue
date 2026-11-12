<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tixg7mmhm"/><path class="jiiwuabvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crystal-ball-duocolor" /></template>
<style>
.jiiwuabvr {
  d: path("M7 17C1.262 12.302 4.584 3 12 3s10.738 9.302 5 14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tixg7mmhm {
  stroke-opacity: 0.4;
  d: path("M5 18a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1Zm4-8a3 3 0 0 1 3-3");
}

</style>
