<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rwv5ytb5v"/><path class="wsrjilphf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:filter-off-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rwv5ytb5v {
  stroke-opacity: 0.4;
  d: path("m4 2l14 14");
}

.wsrjilphf {
  d: path("M12 4h7a1 1 0 0 1 1 1c0 .64-.36 1.36-1 2l-2 2m-3 3c-.117.28 0 .736 0 1v4c0 .613-.774 1.387-2 2c-.919.46-2-.081-2-1v-5c0-.64-.36-1.36-1-2L5 7c-.64-.64-1-1.36-1-2a1 1 0 0 1 1-1h1");
}

</style>
