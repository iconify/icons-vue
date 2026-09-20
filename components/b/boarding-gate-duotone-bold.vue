<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jw3vhybwi"/><path class="nn5miyhkq"/><path class="uxojhab3u"/><path class="v3n4job3g"/><path class="pnevpfb0l"/><path class="cq8r84bse"/><path class="srslrxb7v"/><path class="l90ci7bpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:boarding-gate-duotone-bold" /></template>
<style>
.cq8r84bse {
  d: path("M20 21V4h-4v17");
}

.jw3vhybwi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 21V4h4v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l90ci7bpu {
  d: path("m12 9.5 2.5 2.5 -2.5 2.5");
}

.nn5miyhkq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 21V4h-4v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pnevpfb0l {
  d: path("M4 21V4h4v17");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.srslrxb7v {
  d: path("M10 12h4.5");
}

.uxojhab3u {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 12h4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v3n4job3g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 9.5 2.5 2.5 -2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
