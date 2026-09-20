<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGRLD3dzcO)" class="r4i437pya"/><path class="wz_voru7j"/><path class="yij07uscp"/></g><defs><linearGradient id="SVGRLD3dzcO" x1="7.3" x2="17.408" y1="17.865" y2="13.528" gradientUnits="userSpaceOnUse"><stop class="av23mpzvt"/><stop offset=".48" class="j91mgcc6f"/><stop offset="1" class="zadwo3blv"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:emp-background" /></template>
<style>
.av23mpzvt {
  stop-color: var(--svg-color--0031a5, #0031a5);
}

.ft5dv1b6b {
  fill: none;
}

.j91mgcc6f {
  stop-color: var(--svg-color--009eef, #009eef);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.wz_voru7j {
  fill: var(--svg-color--fff, #fff);
  d: path("M9 14H4.25A8 8 0 0 1 4 12c0-4.42 3.545-8 7.92-8H20l-2.476 2.335l-.065-.03zm11-2a8 8 0 0 1-13.6 5.709l3.1-3.21a3.54 3.54 0 0 0 2.5 1a3.5 3.5 0 0 0 2.775-5.635l.225-.2l2.98-2.98A7.97 7.97 0 0 1 20 12");
}

.yij07uscp {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 11.999a7.999 7.999 0 0 1-15.6 2.5h5.1l.255.224c.76.675 2.195 1.94 4.41 1.94c2.834 0 5.334-2.83 5.334-5.664c0-1.21-.25-2.225-.56-2.98a7.97 7.97 0 0 1 1.06 3.98");
}

.zadwo3blv {
  stop-color: var(--svg-color--009dee, #009dee);
}

</style>
