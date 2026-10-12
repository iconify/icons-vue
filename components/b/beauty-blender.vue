<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="evmlhb0vw"/><path class="d92ep-z3x"/><path class="ldrcttbln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:beauty-blender" /></template>
<style>
.d92ep-z3x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.37 15.5c3.5 2 9.76 2 13.26 0");
}

.evmlhb0vw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c3.75 0 7 5.6 7 10.5a7 7 0 0 1-14 0c0-4.9 3.25-10.5 7-10.5");
}

.ldrcttbln {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 9h.01m2.99 2h.01M10 12.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
