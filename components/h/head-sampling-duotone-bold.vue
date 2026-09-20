<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ubm0zdrys"/><path class="lqcp5xb1v"/><path class="t3vzob-fn"/><path class="asusuabnc"/><path class="g7c6_g9qq"/><path class="pzzcoqbsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:head-sampling-duotone-bold" /></template>
<style>
.asusuabnc {
  d: path("m6 9 3 3 3 -3");
}

.g7c6_g9qq {
  d: path("M9 12v3");
}

.lqcp5xb1v {
  d: path("M4 3h16");
}

.pzzcoqbsw {
  d: path("M13.5 12H18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t3vzob-fn {
  d: path("M2 12a6 6 0 0 1 6 -6h8a6 6 0 0 1 6 6 6 6 0 0 1 -6 6H8a6 6 0 0 1 -6 -6");
}

.ubm0zdrys {
  fill: currentColor;
  d: path("M2 12a6 6 0 0 1 6 -6h8a6 6 0 0 1 6 6 6 6 0 0 1 -6 6H8a6 6 0 0 1 -6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
