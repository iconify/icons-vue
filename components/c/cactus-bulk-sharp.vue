<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jj1qo1bpb"/><path class="fz-3uemrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cactus-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fz-3uemrr {
  d: path("M15 11h1a2 2 0 0 0 2-2V6a1 1 0 0 1 2 0v3a4 4 0 0 1-4 4h-1a1 1 0 0 1 0-2M4 12V8a1 1 0 0 1 2 0v4a2 2 0 0 0 2 2h1a1 1 0 0 1 0 2H8a4 4 0 0 1-4-4m1 10a1 1 0 0 1 0-2h14a1 1 0 0 1 0 2Z");
}

.jj1qo1bpb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 21V6a4 4 0 0 1 8 0v15a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1");
}

</style>
