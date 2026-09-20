<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x-f8kachd"/><path class="j3ck4vuoi"/><path class="mwaecstwf"/><path class="p1z08ccdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:corner-left-up-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j3ck4vuoi {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 9 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mwaecstwf {
  d: path("M20 20H10V4");
}

.p1z08ccdv {
  d: path("m5 9 5 -5 5 5");
}

.x-f8kachd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 20H10V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
