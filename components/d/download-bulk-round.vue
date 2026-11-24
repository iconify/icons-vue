<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m310_5mrs"/><path class="t-qzdgb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:download-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m310_5mrs {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 19h8a3 3 0 0 0 3-3a1 1 0 0 1 2 0a5 5 0 0 1-1.464 3.536A4.98 4.98 0 0 1 16 21H8a4.98 4.98 0 0 1-3.536-1.464A5 5 0 0 1 3 16a1 1 0 0 1 2 0a3 3 0 0 0 3 3");
}

.t-qzdgb7e {
  d: path("m11.293 16.707l-4-4a.999.999 0 1 1 1.414-1.414L11 13.586V4a1 1 0 0 1 2 0v9.586l2.293-2.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0");
}

</style>
