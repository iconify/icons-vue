<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sg4i_ud7e"/><path class="xge8cnb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:locate-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.sg4i_ud7e {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 12a8 8 0 1 1 16 0a8 8 0 0 1-16 0");
}

.xge8cnb7e {
  d: path("M13 3v2a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m-5 9.003v-.006a4 4 0 1 1 0 .006m2.157.775a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556M5 11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm14 0h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2m-6 8v2a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0");
}

</style>
