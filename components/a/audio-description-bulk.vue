<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tixasvbfg"/><path class="rexsh41zl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:audio-description-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rexsh41zl {
  d: path("M2 13v-2a4 4 0 0 1 8 0v5a1 1 0 0 1-2 0v-2H4v2a1 1 0 0 1-2 0Zm2-1h4v-1a2 2 0 1 0-4 0Zm9-5h1a5 5 0 0 1 0 10h-1a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1m1 8a3 3 0 1 0 0-6Z");
}

.tixasvbfg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.45 8.563c.366 1.109.551 2.269.55 3.437a11 11 0 0 1-.55 3.437A10.9 10.9 0 0 1 19.8 18.6a1 1 0 0 1-1.6-1.2A8.96 8.96 0 0 0 20 12a8.96 8.96 0 0 0-1.8-5.4a1 1 0 0 1 1.6-1.2c.72.957 1.277 2.025 1.65 3.163");
}

</style>
