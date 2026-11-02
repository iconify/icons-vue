<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j56e6cb9x"/><path class="bbikbkuko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-horizontal-bulk-sharp" /></template>
<style>
.bbikbkuko {
  d: path("M13 8a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm3 6a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.j56e6cb9x {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 2h9a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1M3 14v-4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1m14 3v4a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1");
}

</style>
