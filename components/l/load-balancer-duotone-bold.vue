<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ipy94dbtd"/><path class="bbmo_zb_v"/><path class="wyac7gyle"/><path class="siulgib_a"/><path class="xrx7ewbce"/><path class="e7pgrp-wx"/><path class="hcqml3bhu"/><path class="p2i6q-ifg"/><path class="ldxs-ebdf"/><path class="dt_d4knyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:load-balancer-duotone-bold" /></template>
<style>
.bbmo_zb_v {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dt_d4knyh {
  d: path("M8 18h13");
}

.e7pgrp-wx {
  d: path("M2 12h6");
}

.hcqml3bhu {
  d: path("M8 6v12");
}

.ipy94dbtd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldxs-ebdf {
  d: path("M8 12h13");
}

.p2i6q-ifg {
  d: path("M8 6h13");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.siulgib_a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 12h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wyac7gyle {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 6h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xrx7ewbce {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 18h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
