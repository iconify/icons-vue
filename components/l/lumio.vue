<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGY789rdBR)" class="e8lz958zx"/><path fill="url(#SVGmkGHGdlw)" class="s6o9nepma"/><path class="r7oku2fsz"/><defs><linearGradient id="SVGY789rdBR" x1="4.964" x2="19.036" y1="12.165" y2="12.277" gradientUnits="userSpaceOnUse"><stop class="zi1c5acua"/><stop offset="1" class="vbd5qwbyz"/></linearGradient><linearGradient id="SVGmkGHGdlw" x1="3" x2="19.036" y1="12.165" y2="12.165" gradientUnits="userSpaceOnUse"><stop class="sw_pnb_jw"/><stop offset="1" class="fqpgn-bey"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lumio" /></template>
<style>
.e8lz958zx {
  d: path("m3 3.9l15.873 5.951v4.298L3 20.1z");
}

.fqpgn-bey {
  stop-color: var(--svg-color--f03f79, #f03f79);
}

.ft5dv1b6b {
  fill: none;
}

.r7oku2fsz {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.873 14.149A2.14 2.14 0 0 0 21 12a2.14 2.14 0 0 0-2.127-2.149A2.14 2.14 0 0 0 16.746 12c0 1.187.952 2.149 2.127 2.149");
}

.s6o9nepma {
  d: path("m3 7.206l15.873 2.645v4.298L3 16.794z");
}

.sw_pnb_jw {
  stop-color: var(--svg-color--f03f79, #f03f79);
  stop-opacity: 0;
}

.vbd5qwbyz {
  stop-color: var(--svg-color--8d29c1, #8d29c1);
}

.zi1c5acua {
  stop-color: var(--svg-color--8d29c1, #8d29c1);
  stop-opacity: 0;
}

</style>
