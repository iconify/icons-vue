<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nnzc6bu3w"/><path class="sueirabcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:column-plus-duocolor-sharp" /></template>
<style>
.nnzc6bu3w {
  stroke-opacity: 0.4;
  d: path("M14 12h6m-3-3v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sueirabcw {
  d: path("M4 4h6v16H4Z");
}

</style>
