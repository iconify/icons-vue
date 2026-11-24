<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k__5w9oyx"/><path class="il0z2mbqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-plus-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.il0z2mbqa {
  d: path("M17 7v2a1 1 0 0 1-2 0V7a3 3 0 1 0-6 0v2a1 1 0 0 1-2 0V7a5 5 0 0 1 10 0m-4 5v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H9a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0");
}

.k__5w9oyx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 13a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5Z");
}

</style>
