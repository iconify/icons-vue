<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="slaabt6cb"/><path class="gf1u2acan"/><path class="y8_56ccsy"/><path class="xl2y-kbjn"/><path class="haq4atb7e"/><path class="taxmbub4q"/><path class="q26t8cbjw"/><path class="vg9r0qb2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:legroom-duotone-regular" /></template>
<style>
.gf1u2acan {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.haq4atb7e {
  d: path("M6 2v11h12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q26t8cbjw {
  d: path("M9 17v3");
}

.slaabt6cb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 2v11h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.taxmbub4q {
  d: path("M6 17h12");
}

.vg9r0qb2v {
  d: path("M15 17v3");
}

.xl2y-kbjn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 17v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y8_56ccsy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 17v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
