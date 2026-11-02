<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mztbabc6z"/><path class="adof2ob-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-drive-bulk-sharp" /></template>
<style>
.adof2ob-m {
  d: path("M3 12h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m4 3h.01a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H11a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.mztbabc6z {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.106 4.553A1 1 0 0 1 7 4h10c.379 0 .725.214.894.553l4 8c.07.139.106.292.106.447v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6c0-.155.036-.308.106-.447ZM6 16a1 1 0 1 0 2 0a1 1 0 0 0-2 0m4 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
