<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="u6np9vxqi"/><path class="f6tki2u5h"/><path class="pgc2z3y8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:deadline" /></template>
<style>
.f6tki2u5h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 7v4.5L14 13m3.75 1.25v3.25");
}

.pgc2z3y8t {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 20.25h.01");
}

.u6np9vxqi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.25 11.5a8.75 8.75 0 1 0-8.75 8.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
