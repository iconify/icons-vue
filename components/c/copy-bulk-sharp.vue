<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zy5j5tbwm"/><path class="m5dxe_bcs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m5dxe_bcs {
  d: path("M21 2a1 1 0 0 1 1 1v14a1 1 0 0 1-2 0V4H7a1 1 0 0 1 0-2Z");
}

.zy5j5tbwm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>
