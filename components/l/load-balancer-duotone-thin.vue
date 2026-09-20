<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pwjia2r6k"/><path class="pj_sixb1z"/><path class="g44ebntoj"/><path class="egcx08b2c"/><path class="tp-jyibgw"/><path class="e7pgrp-wx"/><path class="hcqml3bhu"/><path class="p2i6q-ifg"/><path class="ldxs-ebdf"/><path class="dt_d4knyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:load-balancer-duotone-thin" /></template>
<style>
.dt_d4knyh {
  d: path("M8 18h13");
}

.e7pgrp-wx {
  d: path("M2 12h6");
}

.egcx08b2c {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 12h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g44ebntoj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 6h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hcqml3bhu {
  d: path("M8 6v12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ldxs-ebdf {
  d: path("M8 12h13");
}

.p2i6q-ifg {
  d: path("M8 6h13");
}

.pj_sixb1z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pwjia2r6k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tp-jyibgw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 18h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
