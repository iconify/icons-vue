<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cxo2jiicg"/><path class="nrmo-yb4e"/><path class="leef4tbvz"/><path class="wc2ol_sxo"/><path class="k48hg78vj"/><path class="ppivcbbzp"/><path class="t3rq50btb"/><path class="p8yct170k"/><path class="ajw5g_mzy"/><path class="a-9s6wb0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:guardrail-input-duotone-thin" /></template>
<style>
.a-9s6wb0y {
  d: path("M15 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ajw5g_mzy {
  d: path("M10.5 9.5 13 12l-2.5 2.5");
}

.cxo2jiicg {
  fill: currentColor;
  d: path("M15 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k48hg78vj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 9.5 13 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.leef4tbvz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrmo-yb4e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p8yct170k {
  d: path("M7 12h6");
}

.ppivcbbzp {
  d: path("M5 4v16");
}

.t3rq50btb {
  d: path("M19 4v16");
}

.wc2ol_sxo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
