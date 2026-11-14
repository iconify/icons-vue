<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q45tak3zi"/><path class="ugthcgd2x"/><path class="uhg14jb-c"/><path class="k_0uy2bla"/><path class="z83s79b2s"/><path class="kw4m39bfs"/><path class="etj05ebyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-schema" /></template>
<style>
.etj05ebyh {
  d: path("M10 18h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_0uy2bla {
  fill: currentColor;
  d: path("M6.25 14.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.kw4m39bfs {
  fill: currentColor;
  d: path("M6.25 18a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.q45tak3zi {
  d: path("M7.875 2.5h8.25A4.375 4.375 0 0 1 20.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-8.25A4.375 4.375 0 0 1 3.5 17.125V6.875A4.375 4.375 0 0 1 7.875 2.5");
}

.ugthcgd2x {
  fill: currentColor;
  d: path("M3.5 5A2.5 2.5 0 0 1 6 2.5h12A2.5 2.5 0 0 1 20.5 5v2.5h-17Zm2.75 6a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.uhg14jb-c {
  d: path("M10 11h7");
}

.z83s79b2s {
  d: path("M10 14.5h5");
}

</style>
