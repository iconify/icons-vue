<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vx9rskbcr"/><path class="d5b4fcc2f"/><path class="b_pnozb_e"/><path class="p2leukl8g"/><path class="bm3gehbwy"/><path class="xf07dvr8m"/><path class="z9ittvbis"/><path class="bxa1b1bso"/><path class="x7g1r9bby"/><path class="fr472ib_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:long-polling-duotone-bold" /></template>
<style>
.b_pnozb_e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bm3gehbwy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 16 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bxa1b1bso {
  d: path("M6 5v14");
}

.d5b4fcc2f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fr472ib_x {
  d: path("m13 16 3 3 3 -3");
}

.p2leukl8g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vx9rskbcr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x7g1r9bby {
  d: path("M16 5v14");
}

.xf07dvr8m {
  d: path("M2 5h20");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
