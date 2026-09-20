<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lgv7os48g"/><path class="ixxvh9bhb"/><path class="sqr00ubam"/><path class="ht_qrn_sc"/><path class="o8od38cnm"/><path class="tktvzqb2t"/><path class="f__nic5ty"/><path class="mcne0zbsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lawn-duotone-thin" /></template>
<style>
.f__nic5ty {
  d: path("M12 18V6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ht_qrn_sc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 18c0 -4 1 -7 2 -11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ixxvh9bhb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 18c0 -4 -1 -7 -2 -11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lgv7os48g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mcne0zbsf {
  d: path("M17 18c0 -4 1 -7 2 -11");
}

.o8od38cnm {
  d: path("M4 18h16");
}

.sqr00ubam {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 18V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tktvzqb2t {
  d: path("M7 18c0 -4 -1 -7 -2 -11");
}

</style>
