<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dm-jdd46s"/><path class="ft19zm8rj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fuse-duotone" /></template>
<style>
.dm-jdd46s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 3h12a1 1 0 0 1 1 1v1a1 1 0 0 1-1 1a1 1 0 0 0-1 1v10a1 1 0 0 0 1 1a1 1 0 0 1 1 1v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1a1 1 0 0 1 1-1a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1");
}

.ft19zm8rj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h6a1 1 0 0 1 1 1v1a1 1 0 0 1-1 1a1 1 0 0 0-1 1v10a1 1 0 0 0 1 1a1 1 0 0 1 1 1v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1a1 1 0 0 1 1-1a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1zm1 5l-3 4h4l-3 4");
}

.ft5dv1b6b {
  fill: none;
}

</style>
