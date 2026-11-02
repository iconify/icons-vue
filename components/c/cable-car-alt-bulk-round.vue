<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h9hsr7bnk"/><path class="la4wfjj-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cable-car-alt-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h9hsr7bnk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 12h12a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3m-1 4h3v-2H6a1 1 0 0 0-1 1Zm5 0h4v-2h-4Zm6 0h3v-1a1 1 0 0 0-1-1h-2Z");
}

.la4wfjj-s {
  d: path("M14.01 2a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2Zm-4 1a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Zm9.747 1.03a1 1 0 0 1 .486 1.94L13 7.781V13a1 1 0 0 1-2 0V8.281L4.243 9.97a1 1 0 0 1-.486-1.94Z");
}

</style>
