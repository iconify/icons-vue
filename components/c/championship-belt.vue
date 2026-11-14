<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="swh3zzbaa"/><path class="dy4cmmk2o"/><path class="y5v_nkxrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:championship-belt" /></template>
<style>
.dy4cmmk2o {
  d: path("M5.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

.swh3zzbaa {
  d: path("M6.25 9H3.5q-1 0-1 1v4q0 1 1 1h2.75m11.5-6h2.75q1 0 1 1v4q0 1-1 1h-2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y5v_nkxrd {
  d: path("m12 8.5l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291L12 13.75l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
