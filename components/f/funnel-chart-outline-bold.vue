<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xgrfb-bqu"/><path class="vslz5yb3q"/><path class="x3sflacnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:funnel-chart-outline-bold" /></template>
<style>
.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vslz5yb3q {
  d: path("M6 12h12");
}

.x3sflacnk {
  d: path("M9 18h6");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
