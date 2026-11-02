<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ds9-xbcsd"/><path class="pk-3hg67t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caps-lock-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ds9-xbcsd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 18H9a1 1 0 0 1-1-1v-5H4a1.002 1.002 0 0 1-.707-1.707l8-8a1 1 0 0 1 1.414 0l8 8A1 1 0 0 1 20 12h-4v5a1 1 0 0 1-1 1");
}

.pk-3hg67t {
  d: path("M9 20h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
