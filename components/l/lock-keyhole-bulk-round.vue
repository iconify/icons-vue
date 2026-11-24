<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k__5w9oyx"/><path class="rq-p5bn3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-keyhole-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k__5w9oyx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 13a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5Z");
}

.rq-p5bn3w {
  d: path("M7 7a5 5 0 0 1 10 0v2a1 1 0 0 1-2 0V7a3 3 0 1 0-6 0v2a1 1 0 0 1-2 0Zm6 8.733V17a1 1 0 0 1-2 0v-1.267a2.001 2.001 0 1 1 2 0");
}

</style>
