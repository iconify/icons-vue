<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x7e5sqboh"/><path class="o72w9en-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:charging-station-sharp" /></template>
<style>
.o72w9en-n {
  d: path("M11 5.75L8.75 10h3.5L10 14.25m-6.25 6h12.5m-1.5-10.5h2.5v7.75h2.5v-9m0-3.5V3m-1.5 2h3v3.5h-3z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x7e5sqboh {
  d: path("M5.25 20.25V2.75h9.5v17.5Z");
}

</style>
