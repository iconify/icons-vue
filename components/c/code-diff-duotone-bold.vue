<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qcetzob3x"/><path class="xazd95bpp"/><path class="mlwueibtu"/><path class="msooxxbqf"/><path class="nm1tlbreh"/><path class="e03jjq99j"/><path class="emvotkb4z"/><path class="m26ojxb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:code-diff-duotone-bold" /></template>
<style>
.e03jjq99j {
  d: path("M4 7h6");
}

.emvotkb4z {
  d: path("M4 20 20 4");
}

.m26ojxb3w {
  d: path("M14 17h6");
}

.mlwueibtu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20 20 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.msooxxbqf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 17h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nm1tlbreh {
  d: path("M7 4v6");
}

.qcetzob3x {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 4v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xazd95bpp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
