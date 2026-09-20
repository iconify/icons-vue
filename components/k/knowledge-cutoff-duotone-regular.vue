<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pke92rr1n"/><path class="l5ieewe3y"/><path class="qzl7ogbql"/><path class="qhuovfqbi"/><path class="g-pndgz7k"/><path class="y_uork5-p"/><path class="me2guebva"/><path class="pkr04599e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:knowledge-cutoff-duotone-regular" /></template>
<style>
.g-pndgz7k {
  d: path("M2 12h10");
}

.l5ieewe3y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.me2guebva {
  d: path("m18 9.5 3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pke92rr1n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pkr04599e {
  d: path("m21 9.5 -3 3");
}

.qhuovfqbi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m21 9.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qzl7ogbql {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 9.5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y_uork5-p {
  d: path("M15 7v10");
}

</style>
