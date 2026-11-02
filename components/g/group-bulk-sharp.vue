<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jm76gccrt"/><path class="cz9mwxqmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:group-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cz9mwxqmk {
  d: path("M2 3a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2H4v2a1 1 0 0 1-2 0Zm16-1h3a1 1 0 0 1 1 1v3a1 1 0 0 1-2 0V4h-2a1 1 0 0 1 0-2M2 21v-3a1 1 0 0 1 2 0v2h2a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1m19 1h-3a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0v3a1 1 0 0 1-1 1");
}

.jm76gccrt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 6h7a1 1 0 0 1 1 1v4h2a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-7a1 1 0 0 1-1-1v-4H7a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1");
}

</style>
