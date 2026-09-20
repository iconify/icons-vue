<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="en0t3mfgy"/><path class="c0i67abdl"/><path class="g7_6rsq7d"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="xeoeqgblt"/><path class="yw-dgs_nk"/><path class="vjfpd3ony"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-bar-decreasing-duotone-regular" /></template>
<style>
.c0i67abdl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.en0t3mfgy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 7h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g7_6rsq7d {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 17h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.vjfpd3ony {
  d: path("M4 17h6");
}

.xeoeqgblt {
  d: path("M4 7h14");
}

.yw-dgs_nk {
  d: path("M4 12h10");
}

</style>
