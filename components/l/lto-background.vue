<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGw5wE5d4w)" class="r4i437pya"/><path class="sg312i70w"/></g><defs><linearGradient id="SVGw5wE5d4w" x1="4" x2="20" y1="11.576" y2="11.666" gradientUnits="userSpaceOnUse"><stop class="xblfr07jk"/><stop offset="1" class="p5n95nb6o"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lto-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p5n95nb6o {
  stop-color: var(--svg-color--ba6df6, #ba6df6);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.sg312i70w {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.613 5.022L12.09 6.578l.311.32a.44.44 0 0 0 .622 0l1.525-1.556l-.312-.32a.44.44 0 0 0-.31-.133a.44.44 0 0 0-.312.133m-3.853 0l-.311.316l1.524 1.56a.44.44 0 0 0 .631 0l.307-.316l-1.524-1.556a.45.45 0 0 0-.311-.137a.44.44 0 0 0-.312.133zm5.289 2.04l-2.88 2.947l.582.595a.83.83 0 0 0 1.187 0l2.875-2.946l-.578-.596a.835.835 0 0 0-.919-.188a.8.8 0 0 0-.272.188zm-7.28 0l-.582.596l2.875 2.946a.83.83 0 0 0 1.187 0l.582-.595l-2.875-2.947a.84.84 0 0 0-.596-.253a.82.82 0 0 0-.591.253m3.915.182l-.306.311L12 8l.622-.445l-.31-.31A.44.44 0 0 0 12 7.11a.45.45 0 0 0-.311.133zm5.378 2.685l-4.782 4.897l.969.992a1.376 1.376 0 0 0 1.969 0L20 10.92l-.969-.991a1.4 1.4 0 0 0-.982-.418a1.36 1.36 0 0 0-.987.418m-12.093 0l-.969.99l4.782 4.894a1.377 1.377 0 0 0 1.969 0l.969-.991l-4.782-4.889a1.4 1.4 0 0 0-.987-.422a1.37 1.37 0 0 0-.982.418m6.435.99l-.577.596l1.173.93l1.178-.925l-.583-.6a.83.83 0 0 0-.595-.254a.84.84 0 0 0-.596.254m-.39 5.499l-.965.99L12 19.112l1.956-1.702l-.97-.991A1.4 1.4 0 0 0 12 16c-.364 0-.729.15-.987.418");
}

.xblfr07jk {
  stop-color: var(--svg-color--7cb7ff, #7cb7ff);
}

</style>
