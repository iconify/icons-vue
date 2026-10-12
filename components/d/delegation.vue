<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="mb4tuyzay"/><path class="h-rq1fb0c"/><circle class="kvb7u3b8m"/><path class="b7btm-5wz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:delegation" /></template>
<style>
.b7btm-5wz {
  d: path("M15.5 21.25h5a.5.5 0 0 0 .5-.5C21 19.1 19.65 18 18 18s-3 1.1-3 2.75a.5.5 0 0 0 .5.5");
}

.h-rq1fb0c {
  d: path("M3.5 21.25h6a.75.75 0 0 0 .75-.75c0-3.2-1.75-5.75-3.75-5.75S2.75 17.3 2.75 20.5a.75.75 0 0 0 .75.75M9 4h6a3 3 0 0 1 3 3v2m-2-2l2 2l2-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kvb7u3b8m {
  cx: 18px;
  cy: 13.75px;
  r: 1.75px;
}

.mb4tuyzay {
  cx: 6.5px;
  cy: 9px;
  r: 2.75px;
}

</style>
