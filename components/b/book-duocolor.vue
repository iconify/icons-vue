<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lili71bhf"/><path class="ngnr5ebou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-duocolor" /></template>
<style>
.lili71bhf {
  stroke-opacity: 0.4;
  d: path("M7 21h8a2 2 0 0 0 2-2v-2");
}

.ngnr5ebou {
  d: path("M7 17h10a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2H7a2 2 0 0 0-2 2v14m2-2a2 2 0 1 0 0 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
