<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="buesz2wvk"/><path class="mpa8bmbtq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:decimal-increase-bulk-round" /></template>
<style>
.buesz2wvk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 5v2a3 3 0 1 1-6 0V5a3 3 0 1 1 6 0m8 0v2a3 3 0 1 1-6 0V5a3 3 0 1 1 6 0M8 7a1 1 0 0 0 2 0V5a1 1 0 0 0-2 0Zm8-2v2a1 1 0 0 0 2 0V5a1 1 0 0 0-2 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.mpa8bmbtq {
  d: path("M6 5a3 3 0 1 1 6 0v2a3 3 0 1 1-6 0Zm8 0a3 3 0 1 1 6 0v2a3 3 0 1 1-6 0ZM8 5v2a1 1 0 0 0 2 0V5a1 1 0 0 0-2 0m8 0v2a1 1 0 0 0 2 0V5a1 1 0 0 0-2 0M3.01 8a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm14.283 12.293L18.586 19H3a1 1 0 0 1 0-2h15.586l-1.293-1.293a1 1 0 0 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414");
}

</style>
