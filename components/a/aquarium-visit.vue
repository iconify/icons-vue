<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qelbh0-8f"/><path class="gmyib0bfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aquarium-visit" /></template>
<style>
.gmyib0bfd {
  d: path("M6 12c2-3.5 6.5-3.5 8.5 0l3-2.5v5l-3-2.5c-2 3.5-6.5 3.5-8.5 0Zm3 0h.01");
}

.qelbh0-8f {
  d: path("M2.5 4.5v13a2 2 0 0 0 2 2h15a2 2 0 0 0 2-2v-13m-19 2h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
