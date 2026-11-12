<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i6voyt19l"/><path class="tsnjdg5zu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-plus-corner-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i6voyt19l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 12a.997.997 0 0 0-1 1v8a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v6a1 1 0 0 1-1 1Z");
}

.tsnjdg5zu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v6M3 17l5-5a1.414 1.414 0 0 1 2 0l1 1m3-5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 10h6m-3-3v6");
}

</style>
