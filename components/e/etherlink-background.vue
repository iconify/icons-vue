<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG1DoHHetq)" class="r4i437pya"/><path class="fis-pbb_k"/><path class="q8o-by9-q"/></g><defs><linearGradient id="SVG1DoHHetq" x1="4" x2="26.335" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="hlwacka-r"/><stop offset="1" class="p2jmi1bko"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:etherlink-background" /></template>
<style>
.fis-pbb_k {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4a8 8 0 1 0 0 16a8 8 0 0 0 0-16m0 14.584a6.584 6.584 0 1 1 0-13.168a6.584 6.584 0 0 1 0 13.168");
}

.ft5dv1b6b {
  fill: none;
}

.hlwacka-r {
  stop-color: var(--svg-color--38ff9c, #38ff9c);
}

.p2jmi1bko {
  stop-color: var(--svg-color--171717, #171717);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q8o-by9-q {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.957 7.601a4.416 4.416 0 0 0-4.356 4.45c.007.619.142 1.207.38 1.74c.035.08.14.097.201.034l.97-1a.27.27 0 0 0 .071-.247a2.836 2.836 0 0 1 3.247-3.375a.32.32 0 0 0 .28-.09l.964-.995a.115.115 0 0 0-.038-.187a4.4 4.4 0 0 0-1.72-.33m.088 8.803c2.42-.023 4.382-2.029 4.355-4.45a4.4 4.4 0 0 0-.38-1.74a.124.124 0 0 0-.201-.034l-.97 1a.27.27 0 0 0-.07.248q.057.28.058.577a2.836 2.836 0 0 1-3.306 2.798a.32.32 0 0 0-.28.09l-.964.995a.115.115 0 0 0 .038.186a4.4 4.4 0 0 0 1.72.33m-2.31-3.534l-1.848 1.848a.96.96 0 1 0 1.358 1.358l1.847-1.848a.96.96 0 1 0-1.357-1.358m4.982-4.972l-1.848 1.848a.96.96 0 0 0 1.358 1.358l1.847-1.848a.96.96 0 1 0-1.357-1.358");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
