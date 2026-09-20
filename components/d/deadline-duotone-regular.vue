<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="an1x5nodj"/><path class="aa7su1ohb"/><path class="kuwp6db-s"/><path class="iwanrj-np"/><path class="oe2u-obal"/><path class="u4_zcfcdm"/><path class="qaaffjxln"/><path class="fhbl5kbmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:deadline-duotone-regular" /></template>
<style>
.aa7su1ohb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 7v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.an1x5nodj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.96 5.66a7 7 0 1 1 -5.92 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fhbl5kbmk {
  d: path("M21 3v18");
}

.iwanrj-np {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kuwp6db-s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oe2u-obal {
  d: path("M12.96 5.66a7 7 0 1 1 -5.92 0");
}

.qaaffjxln {
  d: path("M10 12h5");
}

.u4_zcfcdm {
  d: path("M10 7v5");
}

</style>
