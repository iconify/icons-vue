<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xpiamnb3r"/><path class="n8m2x39rs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:generator-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n8m2x39rs {
  d: path("M4 3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0V4H6v3a1 1 0 0 1-2 0Zm4.414 9H10a1.002 1.002 0 0 1 .707 1.707l-3 3a.999.999 0 1 1-1.414-1.414L7.586 14H6a1.002 1.002 0 0 1-.707-1.707l3-3a.999.999 0 1 1 1.414 1.414ZM17 10a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2ZM7 21a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm12 0a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

.xpiamnb3r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6h18a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1");
}

</style>
