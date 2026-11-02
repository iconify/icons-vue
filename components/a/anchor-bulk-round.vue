<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mz07yqb2e"/><path class="tzj6jjbaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:anchor-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mz07yqb2e {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.236 3.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

.tzj6jjbaf {
  d: path("M13 10h2a1 1 0 0 1 0 2h-2v7.939A8.015 8.015 0 0 0 19.939 13H19a1 1 0 0 1 0-2h2a1 1 0 0 1 1 1c0 5.523-4.477 10-10 10S2 17.523 2 12a1 1 0 0 1 1-1h2a1 1 0 0 1 0 2h-.939A8.015 8.015 0 0 0 11 19.939V12H9a1 1 0 0 1 0-2h2V7a1 1 0 0 1 2 0Z");
}

</style>
