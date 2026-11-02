<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a5i76hb6u"/><path class="cpomvobiw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-bitcoin-duocolor-round" /></template>
<style>
.a5i76hb6u {
  stroke-opacity: 0.4;
  d: path("M7 3v2m4-2v2M7 19v2m4-2v2");
}

.cpomvobiw {
  d: path("M7 5v14M7 5h6a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3H7m0 0h7a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3H7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
