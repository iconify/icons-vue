<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ry9pty7ag"/><path class="uuxeqsclb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-garage-open-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ry9pty7ag {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14 13h-4a2 2 0 0 0-2 2v4a2 2 0 1 1-4 0v-8.092c0-.577.249-1.126.683-1.506l6-5.25a2 2 0 0 1 2.634 0l6 5.25c.434.38.683.929.683 1.506V19a2 2 0 1 1-4 0v-4a2 2 0 0 0-2-2");
}

.uuxeqsclb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13h2a2 2 0 0 1 2 2v4a2 2 0 1 0 4 0v-8.092a2 2 0 0 0-.683-1.506l-6-5.25a2 2 0 0 0-2.634 0l-6 5.25A2 2 0 0 0 4 10.908V19a2 2 0 1 0 4 0v-4a2 2 0 0 1 2-2z");
}

</style>
