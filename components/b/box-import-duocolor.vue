<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f_su13hyr"/><path class="ibwtuwbsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-import-duocolor" /></template>
<style>
.f_su13hyr {
  stroke-opacity: 0.4;
  d: path("m18 15l-3 3l3 3m-3-3h6");
}

.ibwtuwbsy {
  d: path("M21 12V7.066a1 1 0 0 0-.557-.897L16.5 4.222m0 0L12.443 2.22a1 1 0 0 0-.886 0l-8 3.95A1 1 0 0 0 3 7.066v9.868a1 1 0 0 0 .557.897l7.546 3.726A.62.62 0 0 0 12 21V10.889M3.16 6.523L12 10.89l8.84-4.366");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
