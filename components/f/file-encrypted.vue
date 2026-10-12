<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="it-qfxbvy"/><path class="wmgztcjui"/><circle class="m6tf8tb7x"/><path class="nww_hh-_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-encrypted" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.it-qfxbvy {
  d: path("M11.75 21.25h-4.5a2.5 2.5 0 0 1-2.5-2.5V5.25a2.5 2.5 0 0 1 2.5-2.5h6.5l5.5 5.5v3.5");
}

.m6tf8tb7x {
  cx: 15.75px;
  cy: 18.5px;
  r: 2.25px;
}

.nww_hh-_u {
  d: path("m17.5 16.75l3-3M19.25 15l1.25 1.25");
}

.wmgztcjui {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-11 4h4");
}

</style>
