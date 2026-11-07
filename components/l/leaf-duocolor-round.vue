<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ppfuhtbvd"/><path class="oqbmi0b8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:leaf-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oqbmi0b8v {
  d: path("M7 17c7 4 13-1 12-12C8 4 3 10 7 17");
}

.ppfuhtbvd {
  stroke-opacity: 0.4;
  d: path("m4 20l3-3m0 0l6-6");
}

</style>
