<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rvdms1b_u"/><path class="ffhad927c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cooking-pot-duocolor-sharp" /></template>
<style>
.ffhad927c {
  d: path("M5 11v9h14v-9M5 11h14M3 14h2m14 0h2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rvdms1b_u {
  stroke-opacity: 0.4;
  d: path("M6 11a6.5 6.5 0 0 1 12 0m-6-4V4m-2 0h4");
}

</style>
