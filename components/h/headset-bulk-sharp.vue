<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y5hubwopv"/><path class="z734667vx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:headset-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.y5hubwopv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 9a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-7a1 1 0 0 1 1-1Zm13 0a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1v-7a1 1 0 0 1 1-1Z");
}

.z734667vx {
  d: path("M5 11a1 1 0 0 1-1-1a8 8 0 0 1 13.657-5.657A7.98 7.98 0 0 1 20 10a1 1 0 0 1-2 0a6 6 0 0 0-1.761-4.247A6 6 0 0 0 6 10a1 1 0 0 1-1 1m15 4a1 1 0 0 1 2 0v6a1 1 0 0 1-1 1h-8a1 1 0 0 1 0-2h7Z");
}

</style>
