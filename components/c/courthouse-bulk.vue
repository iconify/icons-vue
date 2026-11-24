<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wjyrkwbsl"/><path class="wb6nj-7ti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:courthouse-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wb6nj-7ti {
  d: path("M8 17a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Zm5 0a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Zm5 0a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Zm3 5H3a1 1 0 0 1 0-2h18a1 1 0 0 1 0 2");
}

.wjyrkwbsl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8a1 1 0 0 1-.406-1.914l9-4a1 1 0 0 1 .812 0l9 4A1 1 0 0 1 21 8h-3v8a2 2 0 0 1 2 2v3a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-3a2 2 0 0 1 2-2V8Z");
}

</style>
