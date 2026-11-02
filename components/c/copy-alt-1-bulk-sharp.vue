<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kv64h7nxq"/><path class="pczuiznec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-alt-1-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kv64h7nxq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8h12a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1");
}

.pczuiznec {
  d: path("M8 3a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-6a1 1 0 0 1 0-2h5V4H10v5a1 1 0 0 1-2 0Z");
}

</style>
