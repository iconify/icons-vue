<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krpsndb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:castanets-sharp" /></template>
<style>
.krpsndb_o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14h7.5A3.75 4.5 0 0 1 3 14Zm10.5 0H21a3.75 4.5 0 0 1-7.5 0ZM8 14l4-5m4 5l-4-5m0 0a2 2 0 1 1 0-4a2 2 0 1 1 0 4");
}

</style>
