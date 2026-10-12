<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="y9tr6bcfx"><g mask="url(#SVGsZ1vtcCp)"><path class="dtknt5g7a"/><circle class="l0fn-57om"/><path class="ujy3-ns0y"/></g><path class="uuayz4bxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camera-star" /></template>
<style>
.dtknt5g7a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 9.25a2 2 0 0 1 2-2h2.1l1.1-1.85a1.5 1.5 0 0 1 1.3-.75h4.5a1.5 1.5 0 0 1 1.3.75l1.1 1.85h2.1a2 2 0 0 1 2 2v8.5a2.5 2.5 0 0 1-2.5 2.5H5.75a2.5 2.5 0 0 1-2.5-2.5Z");
}

.jf0axzbmx {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
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

.ujy3-ns0y {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 10.5h.01");
}

.uuayz4bxt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.54 13.92l.83 1.82q.15.32.49.36l2 .22q.34.04.09.28l-1.48 1.35q-.26.24-.19.58l.4 1.96q.07.35-.23.17l-1.75-.99q-.3-.17-.6 0l-1.75.99q-.3.18-.23-.17l.4-1.96q.07-.34-.19-.58l-1.48-1.35q-.25-.24.09-.28l2-.22q.34-.04.49-.36l.83-1.82q.14-.32.28 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
