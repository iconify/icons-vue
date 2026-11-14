<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oeucrxbku"/><path class="r3gfncp3z"/><path class="uhg14jb-c"/><path class="nmar70_db"/><path class="z83s79b2s"/><path class="tjtkg5kkd"/><path class="etj05ebyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-schema" /></template>
<style>
.etj05ebyh {
  d: path("M10 18h6");
}

.nmar70_db {
  fill: currentColor;
  d: path("M6.25 14.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.oeucrxbku {
  d: path("M3.5 2.5h17v19h-17Z");
}

.r3gfncp3z {
  fill: currentColor;
  d: path("M3.5 5A2.5 2.5 0 0 1 6 2.5h12A2.5 2.5 0 0 1 20.5 5v2.5h-17Zm2.75 6a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.tjtkg5kkd {
  fill: currentColor;
  d: path("M6.25 18a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.uhg14jb-c {
  d: path("M10 11h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z83s79b2s {
  d: path("M10 14.5h5");
}

</style>
