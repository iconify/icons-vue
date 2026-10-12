<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="fpon-5lih"/><path class="j4u5jublw"/><path class="oq-y3cbpd"/><path class="o69hi0bmg"/><rect class="u-upolb6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lab-scale" /></template>
<style>
.fpon-5lih {
  width: 18.5px;
  height: 8px;
  x: 2.75px;
  y: 13.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.j4u5jublw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 17.25h4.5");
}

.o69hi0bmg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 9.5h11.5M12 9.5v3.75");
}

.oq-y3cbpd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 17.25h.01m2.74 0h.01");
}

.u-upolb6i {
  width: 5.5px;
  height: 4.25px;
  x: 9.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
