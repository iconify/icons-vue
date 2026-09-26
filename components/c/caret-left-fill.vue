<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ebm5oscgz"/><path class="zpkmj173e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caret-left-fill" /></template>
<style>
.ebm5oscgz {
  fill: currentColor;
  d: path("M6.25868 12.456L17.2159 18.9273C17.5635 19.1326 18 18.8787 18 18.4713V5.52868C18 5.12126 17.5635 4.86742 17.2159 5.0727L6.25868 11.544C5.91377 11.7477 5.91377 12.2523 6.25868 12.456Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zpkmj173e {
  d: path("M6.25868 12.456L17.2159 18.9273C17.5635 19.1326 18 18.8787 18 18.4713V5.52868C18 5.12126 17.5635 4.86742 17.2159 5.0727L6.25868 11.544C5.91377 11.7477 5.91377 12.2523 6.25868 12.456Z");
}

</style>
