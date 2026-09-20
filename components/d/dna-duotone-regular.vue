<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p4vev0khg"/><path class="eydnze3ta"/><path class="sw8cph7mb"/><path class="l9y5p1bzr"/><path class="eq8-mlt7s"/><path class="l0v-b4kbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dna-duotone-regular" /></template>
<style>
.eq8-mlt7s {
  d: path("M16 3c-8 4 -8 14 0 18");
}

.eydnze3ta {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 3c-8 4 -8 14 0 18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.l9y5p1bzr {
  d: path("M8 3c8 4 8 14 0 18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p4vev0khg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 3c8 4 8 14 0 18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sw8cph7mb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
