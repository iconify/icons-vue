<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zoz5ar7wf"/><path class="idtt80hqt"/><path class="xj9_gsbwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:current-location-outline-bold" /></template>
<style>
.idtt80hqt {
  d: path("M5.42 11.61a7 7 0 0 1 13.16 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xj9_gsbwr {
  d: path("M2.6 10.58a10 10 0 0 1 18.8 0");
}

.zoz5ar7wf {
  d: path("M9 14a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
