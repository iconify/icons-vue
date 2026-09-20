<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l31czypqh"/><path class="fqi0-7bcf"/><path class="qds1w346b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:diploma-duotone-bold" /></template>
<style>
.fqi0-7bcf {
  d: path("M4 8a3 3 0 0 0 0 6h16a3 3 0 0 0 0 -6Z");
}

.l31czypqh {
  fill: currentColor;
  d: path("M4 8a3 3 0 0 0 0 6h16a3 3 0 0 0 0 -6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qds1w346b {
  d: path("M10 14v6l2 -2 2 2v-6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
