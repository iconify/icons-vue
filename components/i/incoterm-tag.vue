<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="qqgtjgbwf"/><path class="ilihv0v9u"/><path class="l3-rllbtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:incoterm-tag" /></template>
<style>
.ilihv0v9u {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 7h.01");
}

.l3-rllbtr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 15.25L15 10.5m-3.5 0H15V14");
}

.qqgtjgbwf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.25v6.4a1.5 1.5 0 0 0 .44 1.06l9.1 9.1a1.5 1.5 0 0 0 2.12 0l6.4-6.4a1.5 1.5 0 0 0 0-2.12l-9.1-9.1a1.5 1.5 0 0 0-1.06-.44h-6.4a1.5 1.5 0 0 0-1.5 1.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
