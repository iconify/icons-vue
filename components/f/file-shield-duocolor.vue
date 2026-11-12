<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x1cbodbnf"/><path class="qvcpzubvw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-shield-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qvcpzubvw {
  d: path("M13 3H7a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V9m-6-6l6 6m-6-6v4a2 2 0 0 0 2 2h4");
}

.x1cbodbnf {
  stroke-opacity: 0.4;
  d: path("M12 12h2a1 1 0 0 1 1 1v1c0 2-1 3-3 4c-2-1-3-2-3-4v-1a1 1 0 0 1 1-1z");
}

</style>
