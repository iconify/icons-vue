<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r6q4z4mht"/><path class="vpnnq-b4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-bottom-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.r6q4z4mht {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 3h2a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3m10 4h2a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3");
}

.vpnnq-b4m {
  d: path("M3 19h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
