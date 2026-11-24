<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lpcc7-b1f"/><path class="q_dwz-baq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-edit-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lpcc7-b1f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 11a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

.q_dwz-baq {
  d: path("M17 7v2a1 1 0 0 1-2 0V7a3 3 0 1 0-6 0v2a1 1 0 0 1-2 0V7a5 5 0 0 1 10 0m-9 9c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l2 2a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 11 19H9a1 1 0 0 1-1-1Z");
}

</style>
