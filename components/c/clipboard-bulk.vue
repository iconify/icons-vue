<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sy9auzjda"/><path class="qr_2vsbws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qr_2vsbws {
  d: path("M10 2h4a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2");
}

.sy9auzjda {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 7v12a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3");
}

</style>
