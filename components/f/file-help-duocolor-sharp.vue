<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="itiaosczt"/><path class="cesmxqb_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-help-duocolor-sharp" /></template>
<style>
.cesmxqb_w {
  d: path("M13 3H5v18h14V9m-6-6l6 6m-6-6v6h6");
}

.itiaosczt {
  stroke-opacity: 0.4;
  d: path("M9 13a2 2 0 1 1 2 2m0 3h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
