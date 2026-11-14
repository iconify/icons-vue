<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lfemblb8c"/><path class="pvpfk_bdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:find-replace" /></template>
<style>
.lfemblb8c {
  d: path("M3 10.5a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0ZM16 16l5 5M7 10.5h6.5");
}

.pvpfk_bdv {
  d: path("m11 8l2.5 2.5L11 13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
