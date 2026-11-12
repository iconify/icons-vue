<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eur1wbg9u"/><path class="iz84i01ul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-stash-duocolor-round" /></template>
<style>
.eur1wbg9u {
  stroke-opacity: 0.4;
  d: path("M12 8v7m-3-3l3 3l3-3");
}

.iz84i01ul {
  d: path("M10 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-7 8v3a4 4 0 0 0 4 4h10a4 4 0 0 0 4-4v-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
