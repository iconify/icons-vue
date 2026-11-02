<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fst13_7nd"/><path class="r5kqcw9ee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:loop-duocolor-sharp" /></template>
<style>
.fst13_7nd {
  stroke-opacity: 0.4;
  d: path("m8 21l3-3l-3-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r5kqcw9ee {
  d: path("M15 18h6V6H3v12h8");
}

</style>
