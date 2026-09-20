<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<defs><path id="SVG2nd9NcIR" class="mct0g76ey"/></defs><g class="ft5dv1b6b"><path class="lvpypdb_b"/><circle class="ct3_n74px"/><use href="#SVG2nd9NcIR"/><rect class="syr642xgy"/><path clip-rule="evenodd" class="wvetai5bk"/><path class="ck-m7cb2k"/><use href="#SVG2nd9NcIR"/><path clip-rule="evenodd" class="g63e7ulsp"/><path class="xtuew9_gn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:identification-off" /></template>
<style>
.ck-m7cb2k {
  fill: currentColor;
  d: path("M7.75 9.25a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0");
}

.ct3_n74px {
  cx: 6.5px;
  cy: 9.25px;
  r: 1.25px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.g63e7ulsp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1 6.5a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3H4a3 3 0 0 1-3-3zm3-1a1 1 0 0 0-1 1v7a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-7a1 1 0 0 0-1-1z");
}

.lvpypdb_b {
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M9.5 8H12m-2.5 3.75h5m-5-2.5h5m-5 1.25h5");
}

.mct0g76ey {
  fill: currentColor;
  d: path("M8 11.628c0 .63-.672.57-1.5.57s-1.5.06-1.5-.57c0-.631.672-1.428 1.5-1.428s1.5.797 1.5 1.428");
}

.syr642xgy {
  width: 16px;
  height: 11px;
  x: 2px;
  y: 4.5px;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  rx: 2px;
}

.wvetai5bk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 8a.5.5 0 0 1 .5-.5H12a.5.5 0 0 1 0 1H9.5A.5.5 0 0 1 9 8m0 3.75a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5m0-2.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5m0 1.25a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5");
}

.xtuew9_gn {
  fill: currentColor;
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
