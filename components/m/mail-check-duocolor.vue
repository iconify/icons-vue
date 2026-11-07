<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n3erqrbye"/><path class="o5um80ugo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-check-duocolor" /></template>
<style>
.n3erqrbye {
  stroke-opacity: 0.4;
  d: path("m15 6l2 2l4-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o5um80ugo {
  d: path("M21 13v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h6M4 6l4 4c.64.64 1.36 1 2 1h3");
}

</style>
