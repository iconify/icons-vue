<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mkn80r4hx"/><path class="ovlr8fbkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-text-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mkn80r4hx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 19a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3Z");
}

.ovlr8fbkg {
  d: path("M9 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm3 3a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2ZM8 13h8a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m0 4h4a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2");
}

</style>
