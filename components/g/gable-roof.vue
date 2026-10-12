<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="z6aj1beym"/><path class="a4sqm4byg"/><rect class="hudbfgbxb"/><path class="kg5f3mefb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gable-roof" /></template>
<style>
.a4sqm4byg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11h.01");
}

.hudbfgbxb {
  width: 12.5px;
  height: 6px;
  x: 5.75px;
  y: 15.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 0.5px;
}

.kg5f3mefb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 18.25h2m3.5 0h2");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z6aj1beym {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.23 14.68l8.29-9.86q.48-.57.96 0l8.29 9.86q.48.57-.27.57h-17q-.75 0-.27-.57");
}

</style>
