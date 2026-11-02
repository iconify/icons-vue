<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x2af8ibpk"/><path class="j9imw322z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-keyhole-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j9imw322z {
  d: path("M16 6v4a1 1 0 0 1-2 0V6a2 2 0 1 0-4 0v4a1 1 0 0 1-2 0V6a4 4 0 0 1 8 0m-3 9.733V18a1 1 0 0 1-2 0v-2.267a2.001 2.001 0 1 1 2 0");
}

.x2af8ibpk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 9h16a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10a1 1 0 0 1 1-1");
}

</style>
