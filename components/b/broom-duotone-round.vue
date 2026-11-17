<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="huj58jb6v"/><path class="w0_2kdb9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:broom-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.huj58jb6v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 20c-.919 0-1.459-1.081-1-2l2-4c.326-.651 1.15-1.999 2-2h6c.85.001 1.674 1.349 2 2l2 4c.459.919-.081 2-1 2Z");
}

.w0_2kdb9e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 20H6c-.919 0-1.46-1.081-1-2l2-4c.613-1.226 1.387-2 2-2h6c.613 0 1.387.774 2 2l2 4c.46.919-.081 2-1 2zm-2 0v-3m4 3v-3M12 3v9");
}

</style>
