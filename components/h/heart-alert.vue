<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="y9tr6bcfx"><g mask="url(#SVGsZ1vtcCp)" class="nl157099w"><path class="wh5ahubit"/><path class="j8_vnub6o"/></g><path class="yr-noebov"/><path class="fxu54sbac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heart-alert" /></template>
<style>
.fxu54sbac {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 20.25h.01");
}

.j8_vnub6o {
  d: path("M7.75 7.5c-1.15.15-2 1.1-2.1 2.3");
}

.jf0axzbmx {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

.nl157099w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wh5ahubit {
  d: path("M12 20.25c-.4 0-.8-.15-1.1-.4C7.6 17.1 3.25 13.6 3.25 8.9C3.25 6.2 5.3 4 7.9 4c1.6 0 3 .8 4.1 2.2C13.1 4.8 14.5 4 16.1 4c2.6 0 4.65 2.2 4.65 4.9c0 4.7-4.35 8.2-7.65 10.95c-.3.25-.7.4-1.1.4");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yr-noebov {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 14.5v3.25");
}

</style>
