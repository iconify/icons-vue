<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lkl0-zwpl"/><path class="nkzz5tbfp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brackets-dots-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lkl0-zwpl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.01 5a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2Zm-6 6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2Zm-6 6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2Z");
}

.nkzz5tbfp {
  d: path("M5 4a.997.997 0 0 0-1 1v14a1 1 0 0 0 1 1h1a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h1a1 1 0 0 1 0 2Zm14-2a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3h-1a1 1 0 0 1 0-2h1a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1h-1a1 1 0 0 1 0-2Z");
}

</style>
