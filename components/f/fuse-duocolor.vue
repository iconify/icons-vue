<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jps9vkgsi"/><path class="uofpiedgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fuse-duocolor" /></template>
<style>
.jps9vkgsi {
  stroke-opacity: 0.4;
  d: path("m13 8l-3 4h4l-3 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uofpiedgv {
  d: path("M12 3h6a1 1 0 0 1 1 1v1a1 1 0 0 1-1 1a1 1 0 0 0-1 1v10a1 1 0 0 0 1 1a1 1 0 0 1 1 1v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1a1 1 0 0 1 1-1a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1z");
}

</style>
