<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="y9tr6bcfx"><g mask="url(#SVGsZ1vtcCp)" class="nl157099w"><rect class="x2nbrrpmx"/><path class="efdiu7bwr"/></g><path class="yr-noebov"/><path class="fxu54sbac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bug-alert" /></template>
<style>
.efdiu7bwr {
  d: path("M8.75 6.25a3.25 3.25 0 0 1 6.5 0ZM7.25 14h-3.5m13 0h3.5m-12.5 4.25l-3 1.75m11.5-1.75l3 1.75M8.5 10.75L5.25 9m10.25 1.75L18.75 9M12 12.25v6");
}

.fxu54sbac {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 20.25h.01");
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

.x2nbrrpmx {
  width: 9.5px;
  height: 12.5px;
  x: 7.25px;
  y: 8.75px;
  rx: 4.75px;
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
