<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xfs8wlfhn"/><path class="iml3cbclx"/><path class="qobk6sbqp"/><path class="b1ew5xbzw"/><path class="bgtolgbkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:idor-outline-bold" /></template>
<style>
.b1ew5xbzw {
  d: path("M14 13v5");
}

.bgtolgbkt {
  d: path("M8 15.5h8");
}

.iml3cbclx {
  d: path("M8 7a4 4 0 0 1 8 0");
}

.qobk6sbqp {
  d: path("M10 13v5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xfs8wlfhn {
  d: path("M5 11.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

</style>
