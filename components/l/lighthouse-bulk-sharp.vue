<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zzyu_1cck"/><path class="v043xr-jk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lighthouse-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.v043xr-jk {
  d: path("M9 13H7a1 1 0 0 1 0-2h1V8a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v3h1a1 1 0 0 1 0 2Zm1-2h4V9h-4ZM5 8a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm16 0a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Zm0 12a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

.zzyu_1cck {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.209 17.209L8 11.838V9a1.002 1.002 0 0 1-.707-1.707l4-4a1 1 0 0 1 1.414 0l4 4A1 1 0 0 1 16 9v2.838l.632 1.897ZM14 9h-4v2h4ZM6.605 19.186l10.66-3.554l1.684 5.052A1.002 1.002 0 0 1 18 22H6a1.002 1.002 0 0 1-.949-1.316l.368-1.103Z");
}

</style>
