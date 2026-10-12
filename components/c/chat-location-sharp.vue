<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ifob98x5h"/><path class="h2037uj6z"/><path class="m9me6bb5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chat-location-sharp" /></template>
<style>
.h2037uj6z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 15s-3.25-2.9-3.25-5.5a3.25 3.25 0 0 1 6.5 0C15.25 12.1 12 15 12 15Z");
}

.ifob98x5h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25v-2.5h18.5v14H12.5L8 20.85l-1.25 1v-4.1h-4v-2.5Z");
}

.m9me6bb5j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
