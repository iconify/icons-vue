<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o_36udguo"/><path class="nut50-tcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-sun-corner-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nut50-tcb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 21H6a2 2 0 0 1-2-2v-8.092a2 2 0 0 1 .683-1.506l6-5.25a2 2 0 0 1 2.634 0L17.714 8M15.5 16.5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m5 0h.5m-1.672 2.828l.354.354M16.5 20.5v.5m-2.828-1.672l-.354.354M12.5 16.5H12m1.672-2.828l-.354-.354M16.5 12.5V12m2.828 1.672l.354-.354");
}

.o_36udguo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17.714 8H10a2 2 0 0 0-2 2v11H6a2 2 0 0 1-2-2v-8.092c0-.577.249-1.126.683-1.506l6-5.25a2 2 0 0 1 2.634 0Z");
}

</style>
