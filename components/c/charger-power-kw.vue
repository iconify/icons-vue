<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q-76wqpon"/><path class="gryiufbdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charger-power-kw" /></template>
<style>
.gryiufbdg {
  d: path("M11.25 6L8 12h2.5l-1.25 5.5L13 11h-2.5Z");
}

.q-76wqpon {
  d: path("M4 21.5v-17a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v17m-13.5 0h15M16 8h1.5a2 2 0 0 1 2 2v5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
