<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mur--tena"/><path class="etv1o2b_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:joystick-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.etv1o2b_d {
  d: path("M13 9.874V15a1 1 0 0 1-2 0V9.874a4 4 0 1 1 2 0M6 13a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0Z");
}

.mur--tena {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 14h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8");
}

</style>
