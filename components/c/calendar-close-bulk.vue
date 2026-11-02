<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mkn80r4hx"/><path class="mu3yaz40y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-close-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mkn80r4hx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 19a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3Z");
}

.mu3yaz40y {
  d: path("M9 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm3 3a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm-9.293 5.293L12 14.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 16l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 17.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 16l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>
