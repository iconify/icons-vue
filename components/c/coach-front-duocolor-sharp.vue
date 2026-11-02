<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gx2i7mb-b"/><path class="v9kfmgvhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coach-front-duocolor-sharp" /></template>
<style>
.gx2i7mb-b {
  stroke-opacity: 0.4;
  d: path("M8 15h.01M16 15h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v9kfmgvhb {
  d: path("M4 18V7a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v11zm2 0h2v2H6Zm10 0h2v2h-2ZM4 12h16");
}

</style>
