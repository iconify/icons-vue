<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="li6aiebmc"/><path class="nil64oboo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-check-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.li6aiebmc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 12h-7v7a1 1 0 0 1-1 1a9 9 0 0 1-8.316-5.559A9 9 0 1 1 20 11a1 1 0 0 1-1 1");
}

.nil64oboo {
  d: path("M17.45 8.276A7.001 7.001 0 1 0 11 18a1 1 0 0 1 0 2a8.9 8.9 0 0 1-3.504-.708a8.9 8.9 0 0 1-2.86-1.928a9 9 0 0 1-.002-12.726a9.01 9.01 0 0 1 9.87-1.93A8.99 8.99 0 0 1 20 11a1 1 0 0 1-2 0a6.9 6.9 0 0 0-.55-2.724M12 10h2a1 1 0 0 1 0 2h-3a1 1 0 0 1-1-1V7a1 1 0 0 1 2 0Zm5 8.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a1 1 0 0 1 1.414-1.414Z");
}

</style>
