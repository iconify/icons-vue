<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a0f0f2w0j"/><path class="lmnp7qbpj"/><path class="rjga4pbng"/><path class="jfhg8zbol"/><path class="m1u_gbo_m"/><path class="me177l4bh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gauge-duotone-regular" /></template>
<style>
.a0f0f2w0j {
  fill: currentColor;
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jfhg8zbol {
  d: path("M3.54 13.92a9 9 0 0 1 16.92 0");
}

.lmnp7qbpj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3.54 13.92a9 9 0 0 1 16.92 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m1u_gbo_m {
  d: path("m12 17 -5 -5");
}

.me177l4bh {
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rjga4pbng {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 17 -5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
