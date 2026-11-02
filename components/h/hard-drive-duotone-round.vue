<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s7ax2kbse"/><path class="gvadl5gqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-drive-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gvadl5gqk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19H6a3 3 0 0 1-3-3v-3l3-6c.613-1.226 1.774-2 3-2h6c1.226 0 2.387.774 3 2l3 6v3a3 3 0 0 1-3 3zm-9-6h18M7 16h.01M11 16h.01");
}

.s7ax2kbse {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 12a1 1 0 0 1 1 1v2a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5v-2a1 1 0 0 1 1-1ZM6 16a1 1 0 1 0 2 0a1 1 0 0 0-2 0m4 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
