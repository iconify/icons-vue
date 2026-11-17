<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b5wwrobwb"/><path class="hi470ljmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:barn-bulk-sharp" /></template>
<style>
.b5wwrobwb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.514 5.143q.168.1.286.257l3 4a1 1 0 0 1 .2.6v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10a1 1 0 0 1 .2-.6l3-4q.118-.156.286-.257l5-3a.99.99 0 0 1 1.028 0ZM10 10a2 2 0 1 0 3.999.001A2 2 0 0 0 10 10m5 6H9v5h6Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.hi470ljmu {
  d: path("M9 10a3 3 0 1 1 6 0a3 3 0 0 1-6 0m2 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0M3 22a1 1 0 0 1 0-2h5v-4a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v4h5a1 1 0 0 1 0 2Zm11-2v-3h-4v3Z");
}

</style>
