<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uibhdmhak"/><path class="kist3ycms"/><path class="zitzxjbtk"/><path class="u7en4tb0h"/><path class="sj1ms3civ"/><path class="mhila7bcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-quota-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kist3ycms {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.27 9.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mhila7bcl {
  d: path("M20 7v10");
}

.sj1ms3civ {
  d: path("M15.27 9.28a3 3 0 1 1 -2.54 0");
}

.u7en4tb0h {
  d: path("M6.27 9.28a3 3 0 1 1 -2.54 0");
}

.uibhdmhak {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6.27 9.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zitzxjbtk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
