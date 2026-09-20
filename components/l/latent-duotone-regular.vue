<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pgxan_bzk"/><path class="hb1jglb4j"/><path class="q-mksftst"/><path class="pfioxebak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:latent-duotone-regular" /></template>
<style>
.hb1jglb4j {
  fill: currentColor;
  d: path("M21 4.5 13.5 12l7.5 7.5Z");
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

.pfioxebak {
  d: path("M21 4.5 13.5 12l7.5 7.5Z");
}

.pgxan_bzk {
  fill: currentColor;
  d: path("m3 4.5 7.5 7.5L3 19.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q-mksftst {
  d: path("m3 4.5 7.5 7.5L3 19.5Z");
}

</style>
