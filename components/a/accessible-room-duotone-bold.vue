<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ziwwd6b_q"/><path class="cxwbmd0cl"/><path class="m0-fu-bsn"/><path class="n0v-0cb9k"/><path class="d63s22xct"/><path class="nk-dq3bmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:accessible-room-duotone-bold" /></template>
<style>
.cxwbmd0cl {
  fill: currentColor;
  d: path("M6 17a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.d63s22xct {
  d: path("M6 17a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.m0-fu-bsn {
  d: path("M7 4.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.n0v-0cb9k {
  d: path("M9 7v7h7");
}

.nk-dq3bmo {
  d: path("m16 14 3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ziwwd6b_q {
  fill: currentColor;
  d: path("M7 4.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
