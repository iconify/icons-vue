<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e20m3wbce"/><path class="s4miu2bgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:co-driver" /></template>
<style>
.e20m3wbce {
  d: path("M21.5 9.371V19.5l-6 2l-7-2l-6 2V8l6-2l.842.241M8.5 6v13.5m7-.5v2.5");
}

.s4miu2bgg {
  d: path("M5 17.5c2-4 4.5 0 7-2m3.5-1c-2-2.5-3.5-4.5-3.5-7a3.5 3.5 0 0 1 7 0c0 2.5-1.5 4.5-3.5 7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
