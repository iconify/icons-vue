<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h6nnvw4ju"/><path class="p3ta4keoh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bandage-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h6nnvw4ju {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.p3ta4keoh {
  d: path("M6 18V6a1 1 0 0 1 2 0v12a1 1 0 0 1-2 0m10 0V6a1 1 0 0 1 2 0v12a1 1 0 0 1-2 0m-6-9h.01a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2m-4 4h.01a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2");
}

</style>
