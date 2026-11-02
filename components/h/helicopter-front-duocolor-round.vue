<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a1ij8ibsl"/><path class="g5y7rhs5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:helicopter-front-duocolor-round" /></template>
<style>
.a1ij8ibsl {
  stroke-opacity: 0.4;
  d: path("M3 3h18m-9 0v4");
}

.g5y7rhs5d {
  d: path("M6 13a6 6 0 1 1 12 0v2a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2zm2 4v4m8-4v4M6 21h4m4 0h4M6 13h12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
