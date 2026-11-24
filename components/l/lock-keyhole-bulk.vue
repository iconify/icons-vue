<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lpcc7-b1f"/><path class="rq-p5bn3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-keyhole-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lpcc7-b1f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 11a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

.rq-p5bn3w {
  d: path("M7 7a5 5 0 0 1 10 0v2a1 1 0 0 1-2 0V7a3 3 0 1 0-6 0v2a1 1 0 0 1-2 0Zm6 8.733V17a1 1 0 0 1-2 0v-1.267a2.001 2.001 0 1 1 2 0");
}

</style>
