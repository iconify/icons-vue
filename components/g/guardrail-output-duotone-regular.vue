<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nw8-8vb0d"/><path class="its1e1bwq"/><path class="dbfzjzb3n"/><path class="wqtz6zbeu"/><path class="fsqb_bcmz"/><path class="ppivcbbzp"/><path class="t3rq50btb"/><path class="iedujiqkb"/><path class="ognhgbb3v"/><path class="pz3wsjbwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:guardrail-output-duotone-regular" /></template>
<style>
.dbfzjzb3n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fsqb_bcmz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.5 9.5 17 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iedujiqkb {
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.its1e1bwq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nw8-8vb0d {
  fill: currentColor;
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ognhgbb3v {
  d: path("M10.5 12H17");
}

.ppivcbbzp {
  d: path("M5 4v16");
}

.pz3wsjbwy {
  d: path("M14.5 9.5 17 12l-2.5 2.5");
}

.t3rq50btb {
  d: path("M19 4v16");
}

.wqtz6zbeu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.5 12H17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
