<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mh_3yqm3z"/><path class="odoaae72y"/><path class="gswsjr-cj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:health-bar-outline-bold" /></template>
<style>
.gswsjr-cj {
  d: path("M18 7c-1.5 -1.5 -4 -1.5 -4 -3.5 0 -1.5 1.5 -2 2.5 -1 1 -1 2.5 -0.5 2.5 1 0 2 -1 2 -1 3.5");
}

.mh_3yqm3z {
  d: path("M3 10h18v10H3Z");
}

.odoaae72y {
  d: path("M11 10v10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
