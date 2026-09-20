<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qn-h03e3f"/><path class="onmu6lbde"/><path class="y1s8ocbep"/><path class="k0yc21brz"/><path class="crv4i00bu"/><path class="nfb4ipisv"/><path class="b603-acaz"/><path class="pqv-otbrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:llm-trace-duotone-bold" /></template>
<style>
.b603-acaz {
  d: path("M10 12h8");
}

.crv4i00bu {
  d: path("M4 3v18");
}

.k0yc21brz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nfb4ipisv {
  d: path("M7 7h7");
}

.onmu6lbde {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 7h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pqv-otbrp {
  d: path("M13 17h8");
}

.qn-h03e3f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y1s8ocbep {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
