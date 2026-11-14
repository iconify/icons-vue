<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="caltyil3h"/><path class="l2zi7xbsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:demo-live" /></template>
<style>
.caltyil3h {
  d: path("M2.5 3.5h19V17h-19ZM12 17v3.5m-4 0h8");
}

.l2zi7xbsc {
  d: path("m9.5 6.5l5.75 3.75L9.5 14Zm9 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
