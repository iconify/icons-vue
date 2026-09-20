<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nxvwkbbvl"/><path class="l-dfvmblg"/><path class="nxab-kxlu"/><path class="yr0a_60jr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevron-first-duotone-regular" /></template>
<style>
.l-dfvmblg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m19 5 -7 7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nxab-kxlu {
  d: path("M3 5v14");
}

.nxvwkbbvl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yr0a_60jr {
  d: path("m19 5 -7 7 7 7");
}

</style>
