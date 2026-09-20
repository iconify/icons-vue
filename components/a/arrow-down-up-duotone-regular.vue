<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mujv0vbff"/><path class="nxfn3k-cr"/><path class="gof-i4beu"/><path class="tayor0bou"/><path class="gg9qhlhxo"/><path class="v5g-gqbwm"/><path class="pa1ot6bmg"/><path class="wm_1lkfim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-down-up-duotone-regular" /></template>
<style>
.gg9qhlhxo {
  d: path("M8 4v16");
}

.gof-i4beu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mujv0vbff {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nxfn3k-cr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 16 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pa1ot6bmg {
  d: path("M16 4v16");
}

.tayor0bou {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 8 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v5g-gqbwm {
  d: path("m4 16 4 4 4 -4");
}

.wm_1lkfim {
  d: path("m12 8 4 -4 4 4");
}

</style>
