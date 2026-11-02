<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cte3ouyfy"/><path class="bey6c-67d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-vertical-bulk" /></template>
<style>
.bey6c-67d {
  d: path("M7 7a5 5 0 0 1 10 0v2a1 1 0 0 1-2 0V7a3 3 0 1 0-6 0v2a1 1 0 0 1-2 0Zm2 10a3 3 0 1 0 6 0v-2a1 1 0 0 1 2 0v2a5 5 0 0 1-10 0v-2a1 1 0 0 1 2 0Z");
}

.cte3ouyfy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 8v8a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

</style>
