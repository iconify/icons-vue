<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="pg0_1abif"/><path class="b-qsfbbro"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:grail-background" /></template>
<style>
.b-qsfbbro {
  fill: var(--svg-color--000, #000);
  d: path("M13.5 20v-6.5c1.57.17 2.525.81 2.525.81l1-1.125c-1.64-1.17-4.04-1.186-4.04-1.186l-.44-4.45a.975.975 0 1 0-1.515-.814c0 .345.175.65.44.815L11 12s-2.365.01-4.01 1.185l1 1.124s.94-.64 2.51-.81V20C4.36 15.455 3.985 8.855 4 6.665c0-.455.275-.875.69-1.055A18.7 18.7 0 0 1 12 4c3.285 0 6.085 1.065 7.31 1.61c.415.18.69.6.69 1.05c.015 2.2-.375 8.8-6.5 13.34");
}

.ft5dv1b6b {
  fill: none;
}

.pg0_1abif {
  fill: var(--svg-color--ffaf1d, #ffaf1d);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
