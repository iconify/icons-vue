<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z8qqju5mu"/><path class="dkozhebab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coworking-space" /></template>
<style>
.dkozhebab {
  d: path("M4.5 16v5.5M12 16v.3m0 2.6v2.6m-7.5-15a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-1.5 7C3 11 4.75 10 7 10s4 1 4 3.5m3.5-7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-1.5 7c0-2.5 1.75-3.5 4-3.5s4 1 4 3.5M18 21h.01m-1.778-1.768a2.5 2.5 0 0 1 3.536 0m-5.127-1.591a4.75 4.75 0 0 1 6.718 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z8qqju5mu {
  fill: currentColor;
  d: path("M12.3 16H2.5v-2h12.7m5.6 0h.7v.3");
}

</style>
