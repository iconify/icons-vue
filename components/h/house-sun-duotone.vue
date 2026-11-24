<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wih4d2b7q"/><path class="g978ugb4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-sun-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g978ugb4d {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21H6a2 2 0 0 1-2-2v-8.092a2 2 0 0 1 .683-1.506l6-5.25a2 2 0 0 1 2.634 0l6 5.25A2 2 0 0 1 20 10.908V19a2 2 0 0 1-2 2zm-1-8a1 1 0 1 0 2 0a1 1 0 0 0-2 0m5 0h.5m-1.672 2.828l.354.354M12 17v.5m-2.828-1.672l-.354.354M8 13h-.5m1.672-2.828l-.354-.354M12 9v-.5m2.828 1.672l.354-.354");
}

.wih4d2b7q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 21a2 2 0 0 1-2-2v-8.092c0-.577.249-1.126.683-1.506l6-5.25a2 2 0 0 1 2.634 0l6 5.25c.434.38.683.929.683 1.506V19a2 2 0 0 1-2 2Z");
}

</style>
