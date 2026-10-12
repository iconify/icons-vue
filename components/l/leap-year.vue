<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="p4y0o94ut"/><path class="sfq36tbjo"/><path class="gnfs9sbpb"/><path class="fqf0oebvg"/><path class="spnbju8uc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:leap-year" /></template>
<style>
.fqf0oebvg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 15a5.14 5.14 0 0 1 8.5 0");
}

.gnfs9sbpb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 17.75h.01");
}

.p4y0o94ut {
  width: 16.5px;
  height: 15px;
  x: 3.75px;
  y: 5.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.sfq36tbjo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5");
}

.spnbju8uc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 17.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
