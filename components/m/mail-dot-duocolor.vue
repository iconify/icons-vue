<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o-yry0jcj"/><path class="d4b4mjbzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-dot-duocolor" /></template>
<style>
.d4b4mjbzo {
  d: path("M21 13v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o-yry0jcj {
  stroke-opacity: 0.4;
  d: path("m4 6l4 4c.64.64 1.36 1 2 1h3m2-5a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
