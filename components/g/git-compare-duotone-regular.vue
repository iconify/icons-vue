<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vxdgzqbaj"/><path class="lehy25blz"/><path class="i73yinbar"/><path class="q3l2j1zmn"/><path class="tymca9boy"/><path class="qv89ujbjh"/><path class="t1sjjacis"/><path class="epoh96bbt"/><path class="u5a77nl7p"/><path class="x_46rtfdb"/><path class="l576i2b9k"/><path class="y7za30bps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:git-compare-duotone-regular" /></template>
<style>
.epoh96bbt {
  d: path("M16 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.i73yinbar {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 8.5V14h5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l576i2b9k {
  d: path("M18 15.5V10h-5.5");
}

.lehy25blz {
  fill: currentColor;
  d: path("M16 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.q3l2j1zmn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9.5 12 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qv89ujbjh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14.5 8 -2 2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t1sjjacis {
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.tymca9boy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 15.5V10h-5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u5a77nl7p {
  d: path("M6 8.5V14h5.5");
}

.vxdgzqbaj {
  fill: currentColor;
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x_46rtfdb {
  d: path("m9.5 12 2 2 -2 2");
}

.y7za30bps {
  d: path("m14.5 8 -2 2 2 2");
}

</style>
