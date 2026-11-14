<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dur4jqbbu"/><path class="j7dol-blv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:face-smile-frame" /></template>
<style>
.dur4jqbbu {
  d: path("M3 7.5V5a2 2 0 0 1 2-2h2.5m9 0H19a2 2 0 0 1 2 2v2.5m0 9V19a2 2 0 0 1-2 2h-2.5m-9 0H5a2 2 0 0 1-2-2v-2.5M5.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Zm4.25-1.75h.01m4.49 0h.01");
}

.j7dol-blv {
  d: path("M9 14a3.5 3.5 0 0 0 6 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
