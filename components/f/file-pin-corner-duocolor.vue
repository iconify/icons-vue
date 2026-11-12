<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wug0h-ben"/><path class="f0pa7lqfz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-pin-corner-duocolor" /></template>
<style>
.f0pa7lqfz {
  d: path("M13 3H7a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h2m4-18l6 6m-6-6v4a2 2 0 0 0 2 2h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wug0h-ben {
  stroke-opacity: 0.4;
  d: path("M15 13h4v3l1 1c.369.369.369 1 0 1h-6c-.369 0-.369-.631 0-1l1-1zm-1 0h6m-3 5v3");
}

</style>
