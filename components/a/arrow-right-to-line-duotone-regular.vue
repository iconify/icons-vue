<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zwfc0tbtb"/><path class="v0repaboa"/><path class="u8og7obid"/><path class="mhila7bcl"/><path class="jka0cfj-k"/><path class="egsaq3b2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-right-to-line-duotone-regular" /></template>
<style>
.egsaq3b2f {
  d: path("m12 8 4 4 -4 4");
}

.jka0cfj-k {
  d: path("M4 12h12");
}

.mhila7bcl {
  d: path("M20 7v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u8og7obid {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 8 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v0repaboa {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zwfc0tbtb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
