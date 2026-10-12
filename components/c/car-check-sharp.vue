<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="qepuaqbvx"><path class="vuz2t--mx"/><path class="zbm7pqbjy"/></g><path class="efzqbb96b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-check-sharp" /></template>
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

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qepuaqbvx {
  stroke: currentColor;
}

.utmrllbfo {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
  fill: var(--svg-color--000, #000);
}

.vuz2t--mx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12.5L5.6 7.1l.466-1.356L7.5 5.75h9l1.434-.006L18.4 7.1l1.85 5.4v5.75H3.75v-1Zm2.75 5.75v2.5m11-2.5v2.5m-13.25-9.5h15.5");
}

.zbm7pqbjy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 14.75h.01");
}

</style>
