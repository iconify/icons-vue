<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG0kQxGlbD)" class="r4i437pya"/><path class="p4t1llbtp"/><path class="ufn4adcta"/></g><defs><linearGradient id="SVG0kQxGlbD" x1="17.87" x2="7.21" y1="8.483" y2="17.651" gradientUnits="userSpaceOnUse"><stop class="ny8_cjbux"/><stop offset=".35" class="qgoon5b_c"/><stop offset="1" class="ai1d9gm2m"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ctr-background" /></template>
<style>
.ai1d9gm2m {
  stop-color: var(--svg-color--c746a6, #c746a6);
}

.ft5dv1b6b {
  fill: none;
}

.ny8_cjbux {
  stop-color: var(--svg-color--6c7af1, #6c7af1);
}

.p4t1llbtp {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.179 11.528a4.775 4.775 0 0 1-4.428 6.494a4.76 4.76 0 0 1-4.753-4.767A4.758 4.758 0 0 1 12.48 8.54l1.242-3.737A7.515 7.515 0 0 0 4 12c0 4.16 3.36 7.529 7.501 7.529a7.515 7.515 0 0 0 7.483-8z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qgoon5b_c {
  stop-color: var(--svg-color--8958eb, #8958eb);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.ufn4adcta {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.412 10.587a2.588 2.588 0 1 0 0-5.176a2.588 2.588 0 0 0 0 5.176");
}

</style>
