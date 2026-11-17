<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eaj0h0b8p"/><path class="c7yn3pb3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:iron-duocolor-sharp" /></template>
<style>
.c7yn3pb3u {
  d: path("m3 18l7-7h11v7z");
}

.eaj0h0b8p {
  stroke-opacity: 0.4;
  d: path("M21 11V6h-6v5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
