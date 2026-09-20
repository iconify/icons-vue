<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zkfw7-bju"/><path class="r35682biw"/><path class="s99q9ducq"/><path class="l75boxf1g"/><path class="fyu0dwbqf"/><path class="m-rtkii6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:language-server-duotone-bold" /></template>
<style>
.fyu0dwbqf {
  d: path("M9 16v3.5");
}

.l75boxf1g {
  d: path("m16 7 2.5 2.5L16 12");
}

.m-rtkii6v {
  d: path("M15 16v3.5");
}

.r35682biw {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s99q9ducq {
  d: path("M8 7 5.5 9.5 8 12");
}

.zkfw7-bju {
  fill: currentColor;
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
