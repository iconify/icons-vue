<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jhu0uvbgt"/><path class="frzwt_t1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:backspace-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.frzwt_t1l {
  d: path("M13.707 9.293L15 10.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L16.414 12l1.293 1.293a.999.999 0 1 1-1.414 1.414L15 13.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L13.586 12l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

.jhu0uvbgt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 5h7a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 19h-7c-1.039 0-1.992-.578-2.707-1.293l-4-4a2.414 2.414 0 0 1 0-3.414l4-4C8.008 5.578 8.961 5 10 5");
}

</style>
