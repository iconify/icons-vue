<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rovwibb1o"/><path class="m1u6stbvi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-edit-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m1u6stbvi {
  d: path("M7 3a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0Zm8 0a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0Zm5 5a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2ZM8 17c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l2 2a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 11 20H9a1 1 0 0 1-1-1Z");
}

.rovwibb1o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 9a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5Z");
}

</style>
