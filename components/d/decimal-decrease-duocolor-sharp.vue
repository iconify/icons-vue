<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tpoubkban"/><path class="rlc34v9av"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:decimal-decrease-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rlc34v9av {
  d: path("M11 5a2 2 0 1 1 4 0v2a2 2 0 1 1-4 0ZM7 9h.01");
}

.tpoubkban {
  stroke-opacity: 0.4;
  d: path("m6 15l-3 3l3 3m-3-3h18");
}

</style>
