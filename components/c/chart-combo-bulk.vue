<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xcw0ref6u"/><path class="q1riz4b0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-combo-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q1riz4b0j {
  d: path("M4 4v14a1 1 0 0 0 1 1h1v-3a1 1 0 0 1 2 0v3h4v-5a1 1 0 0 1 2 0v5h4v-7a1 1 0 0 1 2 0v7h1a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3V4a1 1 0 0 1 2 0");
}

.xcw0ref6u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.293 4.293a1 1 0 0 1 1.262-.125l5.318 3.545l5.42-5.42a.999.999 0 1 1 1.414 1.414l-6 6a1 1 0 0 1-1.262.125L9.127 6.287l-5.42 5.42a.999.999 0 1 1-1.414-1.414Z");
}

</style>
