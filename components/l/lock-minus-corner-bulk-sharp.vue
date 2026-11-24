<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r4g2h7b0b"/><path class="wt2ym8g3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-minus-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.r4g2h7b0b {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 22H4a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-8v9a1 1 0 0 1-1 1");
}

.wt2ym8g3i {
  d: path("M17 7v2a1 1 0 0 1-2 0V7a3 3 0 1 0-6 0v2a1 1 0 0 1-2 0V7a5 5 0 0 1 10 0m-2 9h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

</style>
