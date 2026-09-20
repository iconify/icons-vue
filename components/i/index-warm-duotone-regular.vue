<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wabxj5bqr"/><path class="v_xe6ynts"/><path class="hgxyr3b_n"/><path class="jabwu9b8s"/><path class="w8pfj5_uc"/><path class="z5jtjknvm"/><path class="nooweob_o"/><path class="u9z5qccfn"/><path class="qnebkmpov"/><path class="zbj6wacas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:index-warm-duotone-regular" /></template>
<style>
.hgxyr3b_n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 15h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jabwu9b8s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 8 2 -2 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nooweob_o {
  d: path("M3 10h12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qnebkmpov {
  d: path("m18 8 2 -2 -2 -2");
}

.u9z5qccfn {
  d: path("M3 15h12");
}

.v_xe6ynts {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 10h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w8pfj5_uc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 16 2 -2 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wabxj5bqr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z5jtjknvm {
  d: path("M3 5h12");
}

.zbj6wacas {
  d: path("m18 16 2 -2 -2 -2");
}

</style>
