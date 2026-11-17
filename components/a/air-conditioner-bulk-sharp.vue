<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n6eojxbwe"/><path class="qjw4_pb6t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:air-conditioner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n6eojxbwe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2h18a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

.qjw4_pb6t {
  d: path("M7 7h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m2 8a3.98 3.98 0 0 1-1.172 2.828A3.98 3.98 0 0 1 5 19a1 1 0 0 1 0-2c.533 0 1.039-.207 1.414-.586c.377-.377.588-.881.586-1.414a1 1 0 0 1 2 0m4 6a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0Zm4-6a2 2 0 0 0 2 2a1 1 0 0 1 0 2a4 4 0 0 1-4-4a1 1 0 0 1 2 0");
}

</style>
