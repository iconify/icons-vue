<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z6qs6gbnt"/><path class="fmbgtccaf"/><path class="ht9zq9bpv"/><path class="c86fwkbjz"/><path class="d6pr-0b9u"/><path class="tp7101bon"/><path class="yb0d-pkkp"/><path class="x1_r36phd"/><path class="ae0h5kb0o"/><path class="x3sflacnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:category-browse-duotone-bold" /></template>
<style>
.ae0h5kb0o {
  d: path("M9 15h6");
}

.c86fwkbjz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 15h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d6pr-0b9u {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fmbgtccaf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 8v14h16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ht9zq9bpv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tp7101bon {
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
}

.x1_r36phd {
  d: path("M9 12h6");
}

.x3sflacnk {
  d: path("M9 18h6");
}

.yb0d-pkkp {
  d: path("M4 8v14h16V8");
}

.z6qs6gbnt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
