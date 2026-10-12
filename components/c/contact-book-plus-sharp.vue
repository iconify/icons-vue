<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="wil2krbkc"><path class="x_j-lkb3f"/><circle class="pc0povb4n"/><path class="dj9619bqg"/></g><path class="b1tcfcbpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:contact-book-plus-sharp" /></template>
<style>
.b1tcfcbpz {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 14.75v5.5m-2.75-2.75h5.5");
}

.c7atyebze {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.dj9619bqg {
  d: path("M8.5 16.25L9.4 14h5.2l.9 2.25");
}

.pc0povb4n {
  cx: 12px;
  cy: 10px;
  r: 2.25px;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.utmrllbfo {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
  fill: var(--svg-color--000, #000);
}

.wil2krbkc {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x_j-lkb3f {
  d: path("M4.75 2.75h14.5v18.5H4.75zM3.25 7.5h3m-3 4.5h3m-3 4.5h3");
}

</style>
