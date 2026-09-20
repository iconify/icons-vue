<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qlvopac9f"/><path class="qnvjj7b8l"/><path class="es63eo13r"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="h0zd56bib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-checkpoint-duotone-regular" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.es63eo13r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 7 -3 3h2.5l-3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h0zd56bib {
  d: path("m15 7 -3 3h2.5l-3 3");
}

.lulmb9b1a {
  d: path("M4 4h16v12H4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qlvopac9f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qnvjj7b8l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
