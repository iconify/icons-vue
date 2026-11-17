<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h7prqcbgz"/><path class="dnti89bie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ev-plug-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dnti89bie {
  d: path("M8.01 8a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2Zm-6 5a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2Z");
}

.h7prqcbgz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.985 4h8.03a5 5 0 0 1 4.475 2.77a9.48 9.48 0 0 1-.032 8.525a9.5 9.5 0 0 1-4.889 4.496a9.4 9.4 0 0 1-3.569.694a9.4 9.4 0 0 1-3.569-.694a9.5 9.5 0 0 1-4.889-4.496A9.48 9.48 0 0 1 3.51 6.77A5 5 0 0 1 7.985 4");
}

</style>
