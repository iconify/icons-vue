<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="uha8iqbqs"/><path fill="url(#SVGYnBVIc5s)" class="tky-cgbjc"/><path fill="url(#SVGNA0sVcia)" class="j499tr7xv"/></g><defs><linearGradient id="SVGYnBVIc5s" x1="12.965" x2="13.29" y1="5.02" y2="18.6" gradientUnits="userSpaceOnUse"><stop class="vzi3mhxsc"/><stop offset="1" class="c7w1inv7w"/></linearGradient><linearGradient id="SVGNA0sVcia" x1="12.14" x2="4.405" y1="5" y2="17.44" gradientUnits="userSpaceOnUse"><stop class="dswc79hmp"/><stop offset="1" class="nk5i8ti2e"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:arpa-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.c7w1inv7w {
  stop-color: var(--svg-color--939493, #939493);
}

.dswc79hmp {
  stop-color: var(--svg-color--dcebf5, #dcebf5);
}

.ft5dv1b6b {
  fill: none;
}

.j499tr7xv {
  d: path("M4 17.5L11.18 5h1.665l-6.3 11h9.18l.855 1.5z");
}

.nk5i8ti2e {
  stop-color: var(--svg-color--b9c6cc, #b9c6cc);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tky-cgbjc {
  d: path("M12.84 5L6.55 16h1.715l4.575-8l6.275 11L20 17.485z");
}

.uha8iqbqs {
  fill: var(--svg-color--5a5967, #5a5967);
  d: path("M4.86 19L4 17.5h12.58L12 9.48l.845-1.485L19.115 19z");
}

.vzi3mhxsc {
  stop-color: var(--svg-color--cbcccd, #cbcccd);
}

</style>
