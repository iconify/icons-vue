<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="upuvm4uhm"/><path class="jo979gbts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-break-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jo979gbts {
  d: path("M18.293 10.293a3.243 3.243 0 0 0-4.586-4.586l-2 2a.999.999 0 1 1-1.414-1.414l2-2a5.243 5.243 0 0 1 7.414 7.414l-2 2a.999.999 0 1 1-1.414-1.414ZM5.707 13.707a3.243 3.243 0 0 0 4.586 4.586l2-2a.999.999 0 1 1 1.414 1.414l-2 2a5.243 5.243 0 0 1-7.414-7.414l2-2a.999.999 0 1 1 1.414 1.414Z");
}

.upuvm4uhm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 3a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0ZM3 9a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2Zm18 6a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Zm-4 6a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

</style>
