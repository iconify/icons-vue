<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="np2e86c6q"/><path class="lbaw04box"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-right-to-line-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lbaw04box {
  d: path("M11.586 12L6.293 6.707a.999.999 0 1 1 1.414-1.414l6 6a1 1 0 0 1 0 1.414l-6 6a.999.999 0 1 1-1.414-1.414Z");
}

.np2e86c6q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 6v12a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0");
}

</style>
