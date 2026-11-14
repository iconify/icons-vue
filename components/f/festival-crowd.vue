<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="szcsgdlac"/><path class="f_tpxpozn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:festival-crowd" /></template>
<style>
.f_tpxpozn {
  d: path("M2.5 20.5c0-3 1.5-4.75 3.5-4.75c.75 0 1.5.25 2 .75m9-5.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4.5 9.5c0-3-1.5-4.75-3.5-4.75c-.75 0-1.5.25-2 .75");
}

.szcsgdlac {
  d: path("M8.75 6.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm-1.25 14c0-4.5 2-7.5 4.5-7.5s4.5 3 4.5 7.5M2.5 11A2.25 2.25 0 1 0 7 11a2.25 2.25 0 1 0-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
