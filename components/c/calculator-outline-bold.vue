<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d3xn50bni"/><path class="kpspt_bpo"/><path class="uxyzhxvwz"/><path class="uto0n9pso"/><path class="a6tpycbpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:calculator-outline-bold" /></template>
<style>
.a6tpycbpp {
  d: path("M12 12v8");
}

.d3xn50bni {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.kpspt_bpo {
  d: path("M7 8h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uto0n9pso {
  d: path("M7 16h10");
}

.uxyzhxvwz {
  d: path("M7 12h10");
}

</style>
