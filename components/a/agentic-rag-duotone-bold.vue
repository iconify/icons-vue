<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jva9i-bck"/><path class="jt4-jw3vg"/><path class="hqg625bvn"/><path class="j0g5onv_m"/><path class="skbifdbcx"/><path class="p9y69lbba"/><path class="lss2klsdg"/><path class="uz0jahmme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agentic-rag-duotone-bold" /></template>
<style>
.hqg625bvn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15.5 11.5a4 4 0 1 1 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j0g5onv_m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11.5 12.5v3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jt4-jw3vg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jva9i-bck {
  fill: currentColor;
  d: path("M14.5 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lss2klsdg {
  d: path("M11.5 12.5v3h3");
}

.p9y69lbba {
  d: path("M15.5 11.5a4 4 0 1 1 -4 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

.uz0jahmme {
  d: path("M14.5 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
