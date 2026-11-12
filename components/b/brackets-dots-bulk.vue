<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lkl0-zwpl"/><path class="arz20qbce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brackets-dots-bulk" /></template>
<style>
.arz20qbce {
  d: path("M4 4v16h2a1 1 0 0 1 0 2H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h2a1 1 0 0 1 0 2Zm16-2a2 2 0 0 1 2 2v16a2 2 0 0 1-2 2h-2a1 1 0 0 1 0-2h2V4h-2a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.lkl0-zwpl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.01 5a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2Zm-6 6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2Zm-6 6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2Z");
}

</style>
