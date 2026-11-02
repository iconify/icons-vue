<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v4ba9eb1d"/><path class="lps7dac0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bath-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lps7dac0b {
  d: path("M3 13a1 1 0 0 1 0-2h1V4a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2a1 1 0 0 1-2 0V5H6v6h15a1 1 0 0 1 0 2Zm6 7a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

.v4ba9eb1d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 12a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

</style>
