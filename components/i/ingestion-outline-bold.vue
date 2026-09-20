<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nvzooz8re"/><path class="mdjxzrmlu"/><path class="pus8sccta"/><path class="ujxlr6_3m"/><path class="cz-gg2_-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ingestion-outline-bold" /></template>
<style>
.cz-gg2_-j {
  d: path("m14 8 2 2 2 -2");
}

.mdjxzrmlu {
  d: path("M8 3v7");
}

.nvzooz8re {
  d: path("M4 18.5A2.5 2.5 0 0 1 6.5 16h11a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-11A2.5 2.5 0 0 1 4 18.5");
}

.pus8sccta {
  d: path("m6 8 2 2 2 -2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ujxlr6_3m {
  d: path("M16 3v7");
}

</style>
