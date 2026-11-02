<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n46n-xqfe"/><path class="g8e6obb6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drill-duocolor-sharp" /></template>
<style>
.g8e6obb6c {
  d: path("M3 4h12v6H3Zm4 6v6m4-6v6m-6 0h8v4H5Z");
}

.n46n-xqfe {
  stroke-opacity: 0.4;
  d: path("M15 5h3v4h-3m3-2h3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
