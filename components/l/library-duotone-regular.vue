<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ub_pbcbdf"/><path class="phjgeccqs"/><path class="gf1u2acan"/><path class="f275eobml"/><path class="woetzacvo"/><path class="dznv025mt"/><path class="taxmbub4q"/><path class="u78lc2bnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:library-duotone-regular" /></template>
<style>
.dznv025mt {
  d: path("M6 14h12");
}

.f275eobml {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 20h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gf1u2acan {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.phjgeccqs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.taxmbub4q {
  d: path("M6 17h12");
}

.u78lc2bnx {
  d: path("M6 20h12");
}

.ub_pbcbdf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 12 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.woetzacvo {
  d: path("m4 12 8 -8 8 8");
}

</style>
