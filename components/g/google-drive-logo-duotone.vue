<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="m9mo3cx1w"/><path class="t0596lbht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:google-drive-logo-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m9mo3cx1w {
  d: path("M24 152h64l-32.88 54.8a7.9 7.9 0 0 1-2.74-2.8l-27.33-47.85A8 8 0 0 1 24 152m144 0l32.88 54.8a7.9 7.9 0 0 0 2.74-2.83l27.32-47.82A8 8 0 0 0 232 152ZM100.43 32a8.06 8.06 0 0 0-3.84 1L128 85.33L159.41 33a8.1 8.1 0 0 0-3.85-1Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t0596lbht {
  d: path("M237.6 143.78L169.13 31.52A15.91 15.91 0 0 0 155.56 24h-55.13a15.89 15.89 0 0 0-13.56 7.52l-.05.07L18.44 143.7a16 16 0 0 0-.33 16.42l27.32 47.82A16 16 0 0 0 59.32 216h137.35a16 16 0 0 0 13.89-8.06l27.32-47.82a15.91 15.91 0 0 0-.28-16.34M219 144h-46.48l-35.19-58.67l22.75-37.92Zm-116.87 0L128 100.88L153.87 144Zm61.34 16l24 40H68.53l24-40ZM128 69.78L110.12 40l35.78-.05ZM95.91 47.41l22.76 37.92L83.47 144H37ZM36.54 160h37.33l-19.15 31.92Zm164.74 31.93L182.12 160h37.41Z");
}

</style>
