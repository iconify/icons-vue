<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d6ij2fblc"/><path class="tmges1b8b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-2-duotone" /></template>
<style>
.d6ij2fblc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 21h-6v-4a1.999 1.999 0 0 0-3-1.732A2 2 0 0 0 10 17v4H4V10.908c0-.577.249-1.126.683-1.506l6-5.25a2 2 0 0 1 2.634 0l6 5.25c.434.38.683.929.683 1.506Z");
}

.ft5dv1b6b {
  fill: none;
}

.tmges1b8b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21h18M4 21V10.908a2 2 0 0 1 .683-1.506l6-5.25a2 2 0 0 1 2.634 0l6 5.25A2 2 0 0 1 20 10.908V21m-10 0v-4a2 2 0 1 1 4 0v4");
}

</style>
