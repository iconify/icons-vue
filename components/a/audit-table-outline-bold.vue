<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zrwkhybyf"/><path class="x50q_4bdr"/><path class="ox73jyb9b"/><path class="dznv025mt"/><path class="y5iyq7b9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:audit-table-outline-bold" /></template>
<style>
.dznv025mt {
  d: path("M6 14h12");
}

.ox73jyb9b {
  d: path("M5.5 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x50q_4bdr {
  d: path("M3 10h18");
}

.y5iyq7b9t {
  d: path("m14 16 2 2 3 -3");
}

.zrwkhybyf {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
