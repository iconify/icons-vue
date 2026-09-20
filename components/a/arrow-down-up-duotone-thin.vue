<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k86txfbxx"/><path class="etn3ob7cq"/><path class="r4q7pxbjl"/><path class="q9sro5bfh"/><path class="gg9qhlhxo"/><path class="v5g-gqbwm"/><path class="pa1ot6bmg"/><path class="wm_1lkfim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-down-up-duotone-thin" /></template>
<style>
.etn3ob7cq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 16 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gg9qhlhxo {
  d: path("M8 4v16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k86txfbxx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pa1ot6bmg {
  d: path("M16 4v16");
}

.q9sro5bfh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 8 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r4q7pxbjl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v5g-gqbwm {
  d: path("m4 16 4 4 4 -4");
}

.wm_1lkfim {
  d: path("m12 8 4 -4 4 4");
}

</style>
