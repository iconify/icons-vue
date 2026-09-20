<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fhtkkzo7b"/><path class="k-xzyt36j"/><path class="uzkjx1-8e"/><path class="l2nbo7bgf"/><path class="l8dn9jbyp"/><path class="ghgpbwtop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:catering-duotone-thin" /></template>
<style>
.fhtkkzo7b {
  fill: currentColor;
  d: path("M11 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ghgpbwtop {
  d: path("M11 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-xzyt36j {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 15a8 8 0 0 1 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l2nbo7bgf {
  d: path("M4 15a8 8 0 0 1 16 0");
}

.l8dn9jbyp {
  d: path("M2 15h20");
}

.uzkjx1-8e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 15h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
