<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j8-lmv0qm"/><path class="slrrf6ejp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-ethereum-duocolor-round" /></template>
<style>
.j8-lmv0qm {
  stroke-opacity: 0.4;
  d: path("m6 12l6 3l6-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.slrrf6ejp {
  d: path("m12 3l6 9l-6 9l-6-9z");
}

</style>
