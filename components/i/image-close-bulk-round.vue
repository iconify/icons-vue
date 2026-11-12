<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wr_1xqtvh"/><path class="jlc6_-blx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-close-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jlc6_-blx {
  d: path("M13.707 6.293L15 7.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L16.414 9l1.293 1.293a.999.999 0 1 1-1.414 1.414L15 10.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L13.586 9l-1.293-1.293a.999.999 0 1 1 1.414-1.414m-11.414 10l1-1a5.243 5.243 0 0 1 7.414 0l5 5a.999.999 0 1 1-1.414 1.414l-5-5a3.24 3.24 0 0 0-4.586 0l-1 1a.999.999 0 1 1-1.414-1.414");
}

.wr_1xqtvh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 2a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5Z");
}

</style>
