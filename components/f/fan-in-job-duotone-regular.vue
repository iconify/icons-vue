<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n5v54kp1e"/><path class="gwtrohb3c"/><path class="x4if7abfp"/><path class="ri2m-q_tv"/><path class="ho-f2ccpq"/><path class="oywe9jbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fan-in-job-duotone-regular" /></template>
<style>
.gwtrohb3c {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 9h3l3 3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ho-f2ccpq {
  d: path("M8 9h3l3 3h3");
}

.n5v54kp1e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oywe9jbcq {
  d: path("M8 15h3l3 -3");
}

.ri2m-q_tv {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

.x4if7abfp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 15h3l3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
