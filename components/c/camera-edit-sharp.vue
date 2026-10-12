<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="qepuaqbvx"><path class="i8qt1xbzh"/><circle class="l0fn-57om"/><path class="ujy3-ns0y"/></g><path class="v1litcb3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camera-edit-sharp" /></template>
<style>
.c7atyebze {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.i8qt1xbzh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 9.25v-2h4.1l1.1-1.85l.433-.751l.867.001h4.5l.867-.001l.433.751l1.1 1.85h4.1v13H3.25v-2.5Z");
}

.l0fn-57om {
  cx: 12px;
  cy: 13.25px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qepuaqbvx {
  stroke: currentColor;
}

.ujy3-ns0y {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 10.5h.01");
}

.utmrllbfo {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
  fill: var(--svg-color--000, #000);
}

.v1litcb3u {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.25 19.75l.5-2.25l2.5-2.5l.929-.817l1.75 1.75l-.929.817l-2.5 2.5Zm1-2.75L18 18.75");
}

</style>
