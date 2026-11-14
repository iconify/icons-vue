<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fh4y646al"/><path class="c58a_stgt"/><path class="qwl5y4_7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drill-pipe-rack" /></template>
<style>
.c58a_stgt {
  d: path("M4 3.5h16a2 2 0 0 1 0 4H4M2 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.fh4y646al {
  d: path("M2 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.qwl5y4_7l {
  d: path("M4 11h16a2 2 0 0 1 0 4H4m-.5 6.5l3-6.5l3 6.5m5 0l3-6.5l3 6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
