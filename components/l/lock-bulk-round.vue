<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ib0p0hbcr"/><path class="ywbu_jj9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ib0p0hbcr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 14a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v3a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5Z");
}

.ywbu_jj9f {
  d: path("M8 6a4 4 0 0 1 8 0v4a1 1 0 0 1-2 0V6a2 2 0 1 0-4 0v4a1 1 0 0 1-2 0Z");
}

</style>
