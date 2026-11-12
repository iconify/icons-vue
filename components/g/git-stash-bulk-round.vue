<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dj-hugbqi"/><path class="vur5ypocr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-stash-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dj-hugbqi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

.vur5ypocr {
  d: path("M11 8a1 1 0 0 1 2 0v4.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L11 12.586Zm-7 6v3a3 3 0 0 0 3 3h10a3.004 3.004 0 0 0 3-3v-3a1 1 0 0 1 2 0v3a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5v-3a1 1 0 0 1 2 0");
}

</style>
