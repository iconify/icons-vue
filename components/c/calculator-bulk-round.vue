<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jnlx1ibsq"/><path class="t5ii0tigx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calculator-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jnlx1ibsq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 7a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5Z");
}

.t5ii0tigx {
  d: path("M16 7a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm-8 4h.01a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m5 1v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m-8.99 3a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2ZM12 15h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
