<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="khounccao"/><path class="ncq0ct0me"/><path class="lwz1s319c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-import" /></template>
<style>
.khounccao {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 20.25h-5.5a2.5 2.5 0 0 1-2.5-2.5v-10a2.5 2.5 0 0 1 2.5-2.5h11.5a2.5 2.5 0 0 1 2.5 2.5v4M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5");
}

.lwz1s319c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.25 20.25l-5-5m0 3.5v-3.5h3.5");
}

.ncq0ct0me {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 14h.01m3.24 0h.01M8 17.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
