<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jz928wudc"/><path class="fsuht_b8c"/><path class="bybw7n7fq"/><path class="a46k8ibzd"/><path class="acyg6nb1v"/><path class="rf0c3ccmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bookshelf-speaker-duotone-bold" /></template>
<style>
.a46k8ibzd {
  d: path("M7 3v18h10V3Z");
}

.acyg6nb1v {
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.bybw7n7fq {
  fill: currentColor;
  d: path("M9 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fsuht_b8c {
  fill: currentColor;
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jz928wudc {
  fill: currentColor;
  d: path("M7 3v18h10V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rf0c3ccmk {
  d: path("M9 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
