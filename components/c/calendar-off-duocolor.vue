<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jvayet_ht"/><path class="fr3z9bc_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-duocolor" /></template>
<style>
.fr3z9bc_y {
  d: path("M19.823 19.823A2 2 0 0 1 18 21H6a2 2 0 0 1-2-2V7a2 2 0 0 1 1.177-1.823M11 5h7a2 2 0 0 1 2 2v7M4 9h5m6 0h5");
}

.jvayet_ht {
  stroke-opacity: 0.4;
  d: path("M16 3v2M2 2l20 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
