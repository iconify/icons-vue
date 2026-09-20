<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG1zWmae1v)" class="r4i437pya"/><path class="agxb3vxbm"/></g><defs><linearGradient id="SVG1zWmae1v" x1="16.627" x2="5.559" y1="7.314" y2="13.743" gradientUnits="userSpaceOnUse"><stop class="vpesd2iao"/><stop offset="1" class="ybqdvudrq"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dfyn-background" /></template>
<style>
.agxb3vxbm {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.71 13.143H6.058L8.343 4h3.685c1.846 0 3.076 1.673 3.222 3.218c.114 1.235-.48 2.958-.79 3.64h3.483L9.015 20z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vpesd2iao {
  stop-color: var(--svg-color--b8566f, #b8566f);
}

.ybqdvudrq {
  stop-color: var(--svg-color--60b9e2, #60b9e2);
}

</style>
