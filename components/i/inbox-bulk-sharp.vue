<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jrbq1jb7d"/><path class="bq7c4ki7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:inbox-bulk-sharp" /></template>
<style>
.bq7c4ki7q {
  d: path("M7 12c.265 0 .52.105.707.293L10.414 15h3.172l2.707-2.707A1 1 0 0 1 17 12h4a1 1 0 0 1 0 2h-3.586l-2.707 2.707A1 1 0 0 1 14 17h-4a1 1 0 0 1-.707-.293L6.586 14H3a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.jrbq1jb7d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>
