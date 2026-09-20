<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qlvopac9f"/><path class="qnvjj7b8l"/><path class="f5tk2o9zy"/><path class="bdpxgpi1q"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="o40l0bbgl"/><path class="a3fwgxb1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:checkpoint-list-duotone-regular" /></template>
<style>
.a3fwgxb1c {
  d: path("M9 11.5h6");
}

.bdpxgpi1q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 11.5h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.crv4i00bu {
  d: path("M4 3v18");
}

.f5tk2o9zy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 8.5h6");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.o40l0bbgl {
  d: path("M9 8.5h6");
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
