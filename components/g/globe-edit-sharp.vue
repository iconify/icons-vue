<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="wil2krbkc"><circle class="dbgvcxwad"/><path class="c3nfbpazq"/></g><path class="v1litcb3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:globe-edit-sharp" /></template>
<style>
.c3nfbpazq {
  d: path("M12 2.75C9.5 5.25 8.25 8.35 8.25 12S9.5 18.75 12 21.25c2.5-2.5 3.75-5.6 3.75-9.25S14.5 5.25 12 2.75ZM2.75 12h18.5");
}

.c7atyebze {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
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

.v1litcb3u {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.25 19.75l.5-2.25l2.5-2.5l.929-.817l1.75 1.75l-.929.817l-2.5 2.5Zm1-2.75L18 18.75");
}

.wil2krbkc {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
