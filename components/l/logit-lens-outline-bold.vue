<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ltbxi_2yl"/><path class="l7q8onb4q"/><path class="gykfelgpq"/><path class="jt7d488ke"/><path class="zdawi4qef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:logit-lens-outline-bold" /></template>
<style>
.gykfelgpq {
  d: path("M13 11v7");
}

.jt7d488ke {
  d: path("M13 7a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.l7q8onb4q {
  d: path("M9 9v9");
}

.ltbxi_2yl {
  d: path("M5 13v5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zdawi4qef {
  d: path("m20 10 2 2");
}

</style>
