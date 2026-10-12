<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="p_kmpymri"/><path class="eau0mhhaw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:inclined-plane-sharp" /></template>
<style>
.eau0mhhaw {
  d: path("m9.84 12.69l2.5 1.66l.63.41l.41-.63l1.66-2.49l.41-.63l-.63-.41l-2.5-1.66l-.63-.41l-.41.63l-1.66 2.49l-.41.63zm6.66 7.56a4.75 4.75 0 0 1 .79-2.62");
}

.p_kmpymri {
  d: path("M3.75 20.25h17.5l-.83-.55L3.58 8.55L2.75 8v12.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
