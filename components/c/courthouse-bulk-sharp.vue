<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="id1wpfj0d"/><path class="wb6nj-7ti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:courthouse-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.id1wpfj0d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.406 2.086l9 4A1 1 0 0 1 21 8h-3v8h1a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h1V8H3a1 1 0 0 1-.406-1.914l9-4a1 1 0 0 1 .812 0");
}

.wb6nj-7ti {
  d: path("M8 17a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Zm5 0a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Zm5 0a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Zm3 5H3a1 1 0 0 1 0-2h18a1 1 0 0 1 0 2");
}

</style>
