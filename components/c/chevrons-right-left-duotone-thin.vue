<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z3ui8tboa"/><path class="lx_kx2bkr"/><path class="h_ozghejt"/><path class="e_z28zb4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevrons-right-left-duotone-thin" /></template>
<style>
.e_z28zb4o {
  d: path("m20 7 -5 5 5 5");
}

.h_ozghejt {
  d: path("m4 7 5 5 -5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lx_kx2bkr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m20 7 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z3ui8tboa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 7 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
