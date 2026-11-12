<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w_z--gdse"/><path class="p4brw5ldj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letters-ab-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p4brw5ldj {
  d: path("m3.051 14.684l3-9a1 1 0 0 1 1.898 0l4 12a1.001 1.001 0 0 1-1.898.632L9.279 16H4.721l-.772 2.316a1.001 1.001 0 0 1-1.898-.632ZM5.387 14h3.226L7 9.162Z");
}

.w_z--gdse {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 5h3a4 4 0 0 1 2.646 7A4 4 0 0 1 18 19h-3a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1m1 8v4h2a2 2 0 0 0 .002-4H18Zm2-2h.002A2 2 0 0 0 18 7h-2v4Z");
}

</style>
