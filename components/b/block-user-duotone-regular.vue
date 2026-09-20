<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k_k2t6-nh"/><path class="etqddkb4f"/><path class="q8-0ejn0y"/><path class="f69zonn4h"/><path class="a7n7fkbfp"/><path class="p8tlrq3-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:block-user-duotone-regular" /></template>
<style>
.a7n7fkbfp {
  d: path("M13 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.etqddkb4f {
  fill: currentColor;
  d: path("M13 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.f69zonn4h {
  d: path("M4 17a4 4 0 0 1 8 0");
}

.k_k2t6-nh {
  fill: currentColor;
  d: path("M5 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p8tlrq3-e {
  d: path("m14 18 6 -6");
}

.q8-0ejn0y {
  d: path("M5 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
