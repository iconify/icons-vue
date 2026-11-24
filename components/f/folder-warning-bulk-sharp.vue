<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ub4z9ebsg"/><path class="rsywueblk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-warning-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rsywueblk {
  d: path("M13 13a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0Zm-.99 2a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

.ub4z9ebsg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 3c.265 0 .52.105.707.293L12.414 5H21a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Z");
}

</style>
