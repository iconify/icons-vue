<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ownp6zban"/><path class="scfi9dh3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crane-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ownp6zban {
  stroke-opacity: 0.4;
  d: path("m3 9l6-6l10 6m-2 0v4a2 2 0 1 1-2 2");
}

.scfi9dh3g {
  d: path("M9 3v18m-3 0h6M3 9h18");
}

</style>
