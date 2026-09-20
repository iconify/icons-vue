<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nlw19-bcl"/><path class="i7i31y8tw"/><path class="ar5_4pb4n"/><path class="u7en4tb0h"/><path class="sj1ms3civ"/><path class="mhila7bcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-quota-duotone-bold" /></template>
<style>
.ar5_4pb4n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i7i31y8tw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15.27 9.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mhila7bcl {
  d: path("M20 7v10");
}

.nlw19-bcl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6.27 9.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sj1ms3civ {
  d: path("M15.27 9.28a3 3 0 1 1 -2.54 0");
}

.u7en4tb0h {
  d: path("M6.27 9.28a3 3 0 1 1 -2.54 0");
}

</style>
