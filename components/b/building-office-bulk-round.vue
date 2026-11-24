<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ltitt6bqu"/><path class="cpctddckd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-office-bulk-round" /></template>
<style>
.cpctddckd {
  d: path("M9 13a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0Zm-8 6a3 3 0 1 1 6 0v1h6a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h6Zm4 1v-1a1 1 0 0 0-2 0v1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ltitt6bqu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 22H4a1 1 0 0 1-1-1V9a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v12a1 1 0 0 1-1 1");
}

</style>
