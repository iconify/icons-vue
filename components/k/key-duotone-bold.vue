<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q2rf3qbee"/><path class="k-gv_lb9q"/><path class="g9c4ykb9u"/><path class="w4_u32yjb"/><path class="txpqn_bqw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:key-duotone-bold" /></template>
<style>
.g9c4ykb9u {
  d: path("M11 12h10");
}

.k-gv_lb9q {
  d: path("M3 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.q2rf3qbee {
  fill: currentColor;
  d: path("M3 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.txpqn_bqw {
  d: path("M20 12v3");
}

.w4_u32yjb {
  d: path("M17 12v3");
}

</style>
