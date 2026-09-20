<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a9off0b5n"/><path class="fspne8bzb"/><path class="juxyw2xbp"/><path class="xdhl9rnnf"/><path class="nh1hchbhr"/><path class="tp19rhqzz"/><path class="gcbumkb_o"/><path class="bod4n0b3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:altitude-duotone-regular" /></template>
<style>
.a9off0b5n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 18 7 -7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bod4n0b3z {
  d: path("M2 18h20");
}

.fspne8bzb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 3v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gcbumkb_o {
  d: path("M16.5 5.5 19 3l2.5 2.5");
}

.juxyw2xbp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16.5 5.5 19 3l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nh1hchbhr {
  d: path("m3 18 7 -7 7 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tp19rhqzz {
  d: path("M19 3v15");
}

.xdhl9rnnf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
