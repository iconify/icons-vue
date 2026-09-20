<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="itcs4-8rc"/><path class="lb46dzmad"/><path class="dzxn5tbwi"/><path class="vnc25opvc"/><path class="xkcm9fbbv"/><path class="p04ylgbfu"/><path class="nqnw98byf"/><path class="hm2fmmbfq"/><path class="i-2_6c56r"/><path class="pm3a-tbmq"/><path class="j6tvmikgv"/><path class="u78lc2bnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:geothermal-duotone-bold" /></template>
<style>
.dzxn5tbwi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 2a2.5 2.5 0 0 1 0 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hm2fmmbfq {
  d: path("M8 12a2.5 2.5 0 0 1 0 -5");
}

.i-2_6c56r {
  d: path("M8 2a2.5 2.5 0 0 1 0 5");
}

.itcs4-8rc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 14h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j6tvmikgv {
  d: path("M16 2a2.5 2.5 0 0 1 0 5");
}

.lb46dzmad {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 12a2.5 2.5 0 0 1 0 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nqnw98byf {
  d: path("M2 14h20");
}

.p04ylgbfu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 20h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pm3a-tbmq {
  d: path("M16 12a2.5 2.5 0 0 1 0 -5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u78lc2bnx {
  d: path("M6 20h12");
}

.vnc25opvc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 12a2.5 2.5 0 0 1 0 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xkcm9fbbv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 2a2.5 2.5 0 0 1 0 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
