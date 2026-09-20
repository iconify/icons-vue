<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k74vnib1e"/><path class="clbajiboq"/><path class="ptubxntjf"/><path class="bqfthgbev"/><path class="l7lvdwbxu"/><path class="sb0fpuinl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:family-outline-bold" /></template>
<style>
.bqfthgbev {
  d: path("M14 15a4 4 0 0 1 8 0");
}

.clbajiboq {
  d: path("M2 15a4 4 0 0 1 8 0");
}

.k74vnib1e {
  d: path("M3 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.l7lvdwbxu {
  d: path("M10 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ptubxntjf {
  d: path("M15 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sb0fpuinl {
  d: path("M9 19a3 3 0 0 1 6 0");
}

</style>
