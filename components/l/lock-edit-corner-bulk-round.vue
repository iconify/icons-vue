<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="did1y4bvn"/><path class="fopn574jx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-edit-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.did1y4bvn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 22a5 5 0 0 1-5-5v-4a5 5 0 0 1 5-5h8a4.9 4.9 0 0 1 2.5.67a4.9 4.9 0 0 1 1.83 1.83a.997.997 0 0 1-.366 1.366a1 1 0 0 1-.5.134H14a3 3 0 0 0-3 3v6a1 1 0 0 1-1 1Z");
}

.fopn574jx {
  d: path("M17 7v2a1 1 0 0 1-2 0V7a3 3 0 1 0-6 0v2a1 1 0 0 1-2 0V7a5 5 0 0 1 10 0m-4 11c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 17 22h-3a1 1 0 0 1-1-1Z");
}

</style>
