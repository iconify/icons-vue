<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h_ii19bhd"/><path class="yezqifbii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-drive-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h_ii19bhd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 12a1 1 0 0 1 1 1v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-4a1 1 0 0 1 1-1ZM6 16a1 1 0 1 0 2 0a1 1 0 0 0-2 0m4 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.yezqifbii {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19H5a2 2 0 0 1-2-2v-4l3-6c.613-1.226 1.387-2 2-2h8c.613 0 1.387.774 2 2l3 6v4a2 2 0 0 1-2 2zm-9-6h18M7 16h.01M11 16h.01");
}

</style>
