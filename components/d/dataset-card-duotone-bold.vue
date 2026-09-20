<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yn64c1dsb"/><path class="d2ixkrbyq"/><path class="tkn_9lu9q"/><path class="w2ifj5b6m"/><path class="ctl_2kq5g"/><path class="zpdz8rbaf"/><path class="fymeavbya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dataset-card-duotone-bold" /></template>
<style>
.ctl_2kq5g {
  d: path("M12 5.5V12");
}

.d2ixkrbyq {
  fill: currentColor;
  d: path("M8 7.5a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2V10a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fymeavbya {
  d: path("M9 18.5h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tkn_9lu9q {
  d: path("M5 4a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.w2ifj5b6m {
  d: path("M8 7.5a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2V10a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.yn64c1dsb {
  fill: currentColor;
  d: path("M5 4a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zpdz8rbaf {
  d: path("M9 15.5h6");
}

</style>
