<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xeqmlybam"/><path class="z0vkypbjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:generator-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.xeqmlybam {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 9a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.z0vkypbjo {
  d: path("M9 2h6c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 20 7a1 1 0 0 1-2 0a3 3 0 0 0-3-3H9a3 3 0 0 0-3 3a1 1 0 0 1-2 0a5 5 0 0 1 1.464-3.536A4.98 4.98 0 0 1 9 2m-.586 10H10a1.002 1.002 0 0 1 .707 1.707l-3 3a.999.999 0 1 1-1.414-1.414L7.586 14H6a1.002 1.002 0 0 1-.707-1.707l3-3a.999.999 0 1 1 1.414 1.414ZM17 10a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2ZM7 21a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm12 0a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

</style>
