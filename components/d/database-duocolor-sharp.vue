<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ku_pfyb9v"/><path class="djg707lrt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-duocolor-sharp" /></template>
<style>
.djg707lrt {
  d: path("M6 7c0 1.657 2.686 3 6 3s6-1.343 6-3s-2.686-3-6-3s-6 1.343-6 3m0 0v10c0 1.657 2.686 3 6 3s6-1.343 6-3V7");
}

.ku_pfyb9v {
  stroke-opacity: 0.4;
  d: path("M6 12c0 1.657 2.686 3 6 3s6-1.343 6-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
