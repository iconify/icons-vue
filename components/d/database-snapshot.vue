<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="giac5pzbr"/><path class="px7uwxlby"/><path class="bery7-8kf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-snapshot" /></template>
<style>
.bery7-8kf {
  d: path("M6.5 12a5.5 2 0 0 0 11 0m-15-4.5V5A2.5 2.5 0 0 1 5 2.5h2.5m9 0H19A2.5 2.5 0 0 1 21.5 5v2.5m0 9V19a2.5 2.5 0 0 1-2.5 2.5h-2.5m-9 0H5A2.5 2.5 0 0 1 2.5 19v-2.5");
}

.giac5pzbr {
  d: path("M6.5 7.5a5.5 2 0 1 0 11 0a5.5 2 0 1 0-11 0Z");
}

.px7uwxlby {
  d: path("M6.5 7.5v9a5.5 2 0 0 0 11 0v-9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
