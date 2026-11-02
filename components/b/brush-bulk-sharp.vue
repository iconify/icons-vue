<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h4jsc1lwp"/><path class="qefa9xb9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brush-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h4jsc1lwp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 14V3a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1h-3v4a3 3 0 1 1-6 0v-4H6a1 1 0 0 1-1-1");
}

.qefa9xb9o {
  d: path("M11 3v3a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m4 0v3a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0M6 9h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

</style>
