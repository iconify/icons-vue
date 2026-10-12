<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="mix73gbvs"/><path class="de9ne4f9m"/><path class="y3b0-dket"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kulfi-stick" /></template>
<style>
.de9ne4f9m {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 9h.01m2.24 2.75h.01M11.25 14h.01");
}

.mix73gbvs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 6.5a3.75 3.75 0 0 1 7.5 0l-.8 9.5a1.25 1.25 0 0 1-1.25 1.15h-3.4A1.25 1.25 0 0 1 9.05 16Z");
}

.y3b0-dket {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 17.15v4.1");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
