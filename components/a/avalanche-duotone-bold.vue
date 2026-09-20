<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nw8-8vb0d"/><path class="x7kl1kqgv"/><path class="cxo2jiicg"/><path class="s3z54lbnm"/><path class="g91uwsb-i"/><path class="kkh8mi1vo"/><path class="iedujiqkb"/><path class="eylqpv51p"/><path class="a-9s6wb0y"/><path class="cjsg0ab2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:avalanche-duotone-bold" /></template>
<style>
.a-9s6wb0y {
  d: path("M15 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.cjsg0ab2y {
  d: path("M2 20h20");
}

.cxo2jiicg {
  fill: currentColor;
  d: path("M15 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.eylqpv51p {
  d: path("M11 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.g91uwsb-i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iedujiqkb {
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.kkh8mi1vo {
  d: path("m3 16 8 -8 3 3 5 5");
}

.nw8-8vb0d {
  fill: currentColor;
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s3z54lbnm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 16 8 -8 3 3 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x7kl1kqgv {
  fill: currentColor;
  d: path("M11 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
