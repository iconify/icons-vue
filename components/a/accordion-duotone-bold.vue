<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s0sz1tb6l"/><path class="dwxywcb3g"/><path class="n45vxib8e"/><path class="arnw7mcql"/><path class="dpohn7bnp"/><path class="lnadppbtp"/><path class="tkg_kabnx"/><path class="i0n60fn-c"/><path class="x22av82oi"/><path class="rhuo4pbym"/><path class="hd4xf-4qm"/><path class="bgh_rqbkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:accordion-duotone-bold" /></template>
<style>
.arnw7mcql {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 13.5 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bgh_rqbkv {
  d: path("m17 17.5 2 2 2 -2");
}

.dpohn7bnp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dwxywcb3g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 3.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hd4xf-4qm {
  d: path("M3 19h11");
}

.i0n60fn-c {
  d: path("m17 3.5 2 2 2 -2");
}

.lnadppbtp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 17.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n45vxib8e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rhuo4pbym {
  d: path("m17 13.5 2 -2 2 2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s0sz1tb6l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tkg_kabnx {
  d: path("M3 5h11");
}

.x22av82oi {
  d: path("M3 12h11");
}

</style>
