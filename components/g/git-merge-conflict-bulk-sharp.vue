<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ws-ux4ksp"/><path class="ojc9-bbno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-merge-conflict-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ojc9-bbno {
  d: path("M4 16V8a1 1 0 0 1 2 0a3 3 0 0 0 3 3h4a1 1 0 0 1 0 2H9a4.97 4.97 0 0 1-3-.999V16a1 1 0 0 1-2 0m13.707-6.707L19 10.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L20.414 12l1.293 1.293a.999.999 0 1 1-1.414 1.414L19 13.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L17.586 12l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

.ws-ux4ksp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m0 12a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
