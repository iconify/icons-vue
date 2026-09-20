<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG3LPDkdii)" class="r4i437pya"/><path class="g3ofbd1ba"/></g><defs><linearGradient id="SVG3LPDkdii" x1="11.991" x2="11.991" y1="4.081" y2="19.91" gradientUnits="userSpaceOnUse"><stop class="b1-ninghz"/><stop offset=".88" class="iu6kt6yol"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hdx-background" /></template>
<style>
.b1-ninghz {
  stop-color: var(--svg-color--f7f5f6, #f7f5f6);
}

.ft5dv1b6b {
  fill: none;
}

.g3ofbd1ba {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.61 19.897a.79.79 0 0 0 .781 0l6.328-3.613a.78.78 0 0 0 .391-.671V8.387a.77.77 0 0 0-.39-.666l-6.33-3.618a.79.79 0 0 0-.782 0L5.281 7.716a.78.78 0 0 0-.39.671v7.226a.77.77 0 0 0 .39.666zm.035-14.118a.74.74 0 0 1 .728 0l5.044 2.786a.7.7 0 0 1 .356.627v5.59a.72.72 0 0 1-.365.622l-5.052 2.817a.74.74 0 0 1-.73 0l-5.038-2.786a.71.71 0 0 1-.36-.626v-5.59a.72.72 0 0 1 .369-.623l5.052-2.817zm-.036 10.563a.74.74 0 0 0 .729 0l3.288-1.867a.72.72 0 0 0 .374-.609v-3.732a.7.7 0 0 0-.365-.618l-.969-.64v4.68l-1.777.973v-2.09l-1.778.4v3.245l.503.266zm-3.288-1.867l1.013.645v-4.786l1.777-.978v1.835l1.778-.378V7.898l-.547-.244a.74.74 0 0 0-.728 0L8.325 9.52a.7.7 0 0 0-.266.258C8 9.876 8 9.983 8 10.09v3.822c0 .106 0 .213.053.31c.067.107.156.2.267.263z");
}

.iu6kt6yol {
  stop-color: var(--svg-color--a69696, #a69696);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
