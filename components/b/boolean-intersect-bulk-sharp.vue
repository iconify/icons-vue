<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="enskswb5e"/><path class="aeym94fsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-intersect-bulk-sharp" /></template>
<style>
.aeym94fsu {
  d: path("M2 3a1 1 0 0 1 1-1h4a1 1 0 0 1 0 2H4v3a1 1 0 0 1-2 0Zm9-1h4a1 1 0 0 1 1 1v2a1 1 0 0 1-2 0V4h-3a1 1 0 0 1 0-2m8 6h2a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0v-3h-1a1 1 0 0 1 0-2M2 11a1 1 0 0 1 2 0v3h1a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1Zm19 11h-4a1 1 0 0 1 0-2h3v-3a1 1 0 0 1 2 0v4a1 1 0 0 1-1 1M8 19a1 1 0 0 1 2 0v1h3a1 1 0 0 1 0 2H9a1 1 0 0 1-1-1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.enskswb5e {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 8h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1");
}

</style>
