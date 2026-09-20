<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="pb6gymb1y"/><path class="q0hwhdxtt"/><path class="hn4s-plkd"/><path class="w7crjybfe"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bithumb-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hn4s-plkd {
  fill: var(--svg-color--fff, #fff);
  d: path("m15.506 7.903l-2.896-.05l.651-2.15A1.32 1.32 0 0 0 12.004 4H9.361L6.34 14.854s-1.083 4.641 3.022 5.061c0 0 6.49 1.327 8.571-6.514c0 0 1.1-4.742-2.426-5.498m-1.98 5.383S13.41 15.29 11.9 15.64a.98.98 0 0 1-.666-.068c-.237-.121-.482-.372-.476-.898a1.7 1.7 0 0 1 .073-.448l.558-2.084h1.523s.69.225.614 1.144");
}

.pb6gymb1y {
  fill: var(--svg-color--f47320, #f47320);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q0hwhdxtt {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.673 7.81H8.95l-1.77 4.332s-.926-.015-1.21-.824a1.3 1.3 0 0 1-.019-.742z");
}

.w7crjybfe {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.071 11.215c-.277-3.186-2.566-3.312-2.566-3.312l-2.895-.05l-1.244 4.314h1.518c.28.015.788.476.623 1.29");
}

</style>
