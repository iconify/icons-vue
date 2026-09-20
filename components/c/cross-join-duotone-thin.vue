<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nrmo-yb4e"/><path class="leef4tbvz"/><path class="ofc1f3max"/><path class="tcoeiw6rn"/><path class="ppivcbbzp"/><path class="t3rq50btb"/><path class="aeqgdde5a"/><path class="pd0q9ub5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cross-join-duotone-thin" /></template>
<style>
.aeqgdde5a {
  d: path("m7 6 10 10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
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

.ofc1f3max {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 6 10 10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pd0q9ub5m {
  d: path("M17 6 7 16");
}

.ppivcbbzp {
  d: path("M5 4v16");
}

.t3rq50btb {
  d: path("M19 4v16");
}

.tcoeiw6rn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 6 7 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
