<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u6c_mxbde"/><path class="za799wbjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-hat-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u6c_mxbde {
  stroke-opacity: 0.4;
  d: path("M10 11V5a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v6");
}

.za799wbjz {
  d: path("M5 16v-5a5 5 0 0 1 5-5m4 0a5 5 0 0 1 5 5v5M3 18a2 2 0 0 1 2-2h14a2 2 0 1 1 0 4H5a2 2 0 0 1-2-2");
}

</style>
