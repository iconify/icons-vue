<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cr10akffk"/><path class="favqejboq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-todo-duocolor-sharp" /></template>
<style>
.cr10akffk {
  stroke-opacity: 0.4;
  d: path("M3 4h6v6H3Zm0 13l2 2l4-4");
}

.favqejboq {
  d: path("M13 7h8m-8 10h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
