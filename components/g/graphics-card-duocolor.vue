<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cwp5bj8es"/><path class="e9j_7yb9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:graphics-card-duocolor" /></template>
<style>
.cwp5bj8es {
  stroke-opacity: 0.4;
  d: path("M6 11a2 2 0 1 0 4 0a2 2 0 0 0-4 0m8 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.e9j_7yb9a {
  d: path("M3 7a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm0-4v18m4-4v3a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1v-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
