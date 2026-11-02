<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h3ynmu6py"/><path class="y0i6bqbvi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-right-duocolor-sharp" /></template>
<style>
.h3ynmu6py {
  stroke-opacity: 0.4;
  d: path("M20 3v18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y0i6bqbvi {
  d: path("M4 4h12v6H4Zm4 10h8v6H8Z");
}

</style>
