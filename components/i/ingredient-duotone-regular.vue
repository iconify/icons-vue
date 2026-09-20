<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="as04bxwqk"/><path class="zo-o-sdgc"/><path class="q059s7b6t"/><path class="cp7scyw-s"/><path class="youb8ccbq"/><path class="z9rf4z-yw"/><path class="g-a4wz-fw"/><path class="x_kkpk0ip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ingredient-duotone-regular" /></template>
<style>
.as04bxwqk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 14h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cp7scyw-s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 14 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g-a4wz-fw {
  d: path("M8 14a3 3 0 0 1 6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q059s7b6t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 14a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x_kkpk0ip {
  d: path("m16 14 5 -5");
}

.youb8ccbq {
  d: path("M6 14h10");
}

.z9rf4z-yw {
  d: path("M16 14a5 5 0 0 1 -10 0");
}

.zo-o-sdgc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 14a5 5 0 0 1 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
