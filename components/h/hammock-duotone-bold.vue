<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fjm39d3xn"/><path class="cqsmwnbfr"/><path class="j62o-lbfc"/><path class="ac_h-hbrg"/><path class="r3uz_wvor"/><path class="vvv_0v-7b"/><path class="auc4o2swl"/><path class="bu35rpbki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hammock-duotone-bold" /></template>
<style>
.ac_h-hbrg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12c0 7 16 7 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.auc4o2swl {
  d: path("M4 8c0 8 16 8 16 0");
}

.bu35rpbki {
  d: path("M4 12c0 7 16 7 16 0");
}

.cqsmwnbfr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 6v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fjm39d3xn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 6v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j62o-lbfc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 8c0 8 16 8 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3uz_wvor {
  d: path("M4 6v15");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vvv_0v-7b {
  d: path("M20 6v15");
}

</style>
