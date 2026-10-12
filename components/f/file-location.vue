<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="it-qfxbvy"/><path class="h9en22pmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-location" /></template>
<style>
.h9en22pmw {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-11 4h4m2.5 5.5h5.5m-4.5 0l.5-3.5h2.5l.5 3.5m-1.75 0v3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.it-qfxbvy {
  d: path("M11.75 21.25h-4.5a2.5 2.5 0 0 1-2.5-2.5V5.25a2.5 2.5 0 0 1 2.5-2.5h6.5l5.5 5.5v3.5");
}

</style>
