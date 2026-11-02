<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ocmf4mbve"/><path class="pa84irn8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gitlab-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ocmf4mbve {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m2.035 13.737l3-11a1.002 1.002 0 0 1 1.884-.131L9.659 9h4.682l2.74-6.394a1 1 0 0 1 1.884.131l3 11a1 1 0 0 1-.351 1.052l-9 7a1 1 0 0 1-1.228 0l-9-7a1 1 0 0 1-.351-1.052");
}

.pa84irn8f {
  d: path("M5.035 2.737a1.002 1.002 0 0 1 1.884-.131L9.659 9h4.682l2.74-6.394a1 1 0 0 1 1.884.131l3 11a1 1 0 0 1-1.93.526L17.79 6.029l-1.871 4.365A1 1 0 0 1 15 11H9a1 1 0 0 1-.919-.606L6.21 6.029l-2.245 8.234a1 1 0 0 1-1.93-.526Z");
}

</style>
