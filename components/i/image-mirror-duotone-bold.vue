<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="do7jur_bk"/><path class="z-ephs7jm"/><path class="aho6qjb9y"/><path class="s229edbfl"/><path class="odx_lab8a"/><path class="lmn7kfb_m"/><path class="gau_gkswx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:image-mirror-duotone-bold" /></template>
<style>
.aho6qjb9y {
  d: path("M8 10v9");
}

.do7jur_bk {
  fill: currentColor;
  d: path("M2 12a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gau_gkswx {
  d: path("M10.5 3.5 8 6l2.5 2.5");
}

.lmn7kfb_m {
  d: path("M13.5 3.5 16 6l-2.5 2.5");
}

.odx_lab8a {
  d: path("M10 6h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s229edbfl {
  d: path("M15 10v9");
}

.z-ephs7jm {
  d: path("M2 12a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
