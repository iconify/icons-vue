<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ongr6rbsx"/><path class="gupbox6-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:blinds-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gupbox6-a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h18M5 3v10a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V3M5 7h14M5 11h14m-7 4v2m-2 2a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.ongr6rbsx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 3v10a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V3Zm-9 16a2 2 0 1 1 3.999-.001A2 2 0 0 1 10 19");
}

</style>
