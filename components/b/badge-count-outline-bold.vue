<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p_u79-b2o"/><path class="yhgzmt2de"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:badge-count-outline-bold" /></template>
<style>
.p_u79-b2o {
  d: path("M2 9a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yhgzmt2de {
  d: path("M17 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
