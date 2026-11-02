<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ru_sq_byx"/><path class="ljv1ika9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:castle-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ljv1ika9a {
  d: path("M5 11V3a1 1 0 0 1 2 0v1h2V3a1 1 0 0 1 2 0v1h2V3a1 1 0 0 1 2 0v1h2V3a1 1 0 0 1 2 0v8a1 1 0 0 1-2 0V6H7v5a1 1 0 0 1-2 0m3 10v-3a4 4 0 0 1 8 0v3a1 1 0 0 1-2 0v-3a2 2 0 1 0-4 0v3a1 1 0 0 1-2 0");
}

.ru_sq_byx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 11a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>
