<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ke8s6xb3g"/><path class="tgnr5bbny"/><path class="im9mur2vv"/><path class="vplm92n7f"/><path class="bazu4hbio"/><path class="t6wf8ob_n"/><path class="nqnw98byf"/><path class="hm2fmmbfq"/><path class="i-2_6c56r"/><path class="pm3a-tbmq"/><path class="j6tvmikgv"/><path class="u78lc2bnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:geothermal-duotone-thin" /></template>
<style>
.bazu4hbio {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 2a2.5 2.5 0 0 1 0 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hm2fmmbfq {
  d: path("M8 12a2.5 2.5 0 0 1 0 -5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-2_6c56r {
  d: path("M8 2a2.5 2.5 0 0 1 0 5");
}

.im9mur2vv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 2a2.5 2.5 0 0 1 0 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j6tvmikgv {
  d: path("M16 2a2.5 2.5 0 0 1 0 5");
}

.ke8s6xb3g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 14h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nqnw98byf {
  d: path("M2 14h20");
}

.pm3a-tbmq {
  d: path("M16 12a2.5 2.5 0 0 1 0 -5");
}

.t6wf8ob_n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 20h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tgnr5bbny {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 12a2.5 2.5 0 0 1 0 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u78lc2bnx {
  d: path("M6 20h12");
}

.vplm92n7f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 12a2.5 2.5 0 0 1 0 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
