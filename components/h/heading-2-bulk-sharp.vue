<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tqo_pztyp"/><path class="y4tx-xbdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heading-2-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.tqo_pztyp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 12v1c0 .265-.105.52-.293.707L17.414 18H21a1 1 0 0 1 0 2h-6a1.002 1.002 0 0 1-.707-1.707L20 12.586V12a2 2 0 0 0-4 0a1 1 0 0 1-2 0a4 4 0 0 1 8 0");
}

.y4tx-xbdi {
  d: path("M4 11h6V5a1 1 0 0 1 2 0v14a1 1 0 0 1-2 0v-6H4v6a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Z");
}

</style>
