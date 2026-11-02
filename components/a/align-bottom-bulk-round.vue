<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ph--7j4dz"/><path class="vpnnq-b4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-bottom-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ph--7j4dz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 7v6a4 4 0 0 1-8 0V7a4 4 0 0 1 8 0m10 4v2a4 4 0 0 1-8 0v-2a4 4 0 0 1 8 0");
}

.vpnnq-b4m {
  d: path("M3 19h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
