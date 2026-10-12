<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="wil2krbkc"><path class="g6_ak4fap"/><path class="o0aijxb6o"/></g><path class="efzqbb96b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gift-check-sharp" /></template>
<style>
.c7atyebze {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.efzqbb96b {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.75 17.75l1.75 1.75l3.5-3.75");
}

.g6_ak4fap {
  d: path("M3.25 7.25h17.5v4.25H3.25zM4.75 14h14.5v7.25H4.75v-2Z");
}

.o0aijxb6o {
  d: path("M12 7.25v14m0-14H8.75a2 2 0 1 1 0-4c1.75 0 2.75 2 3.25 4m0 0h3.25a2 2 0 1 0 0-4c-1.75 0-2.75 2-3.25 4");
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

</style>
