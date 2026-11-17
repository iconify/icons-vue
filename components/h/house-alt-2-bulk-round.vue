<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q-02b_b7l"/><path class="rrho5ub6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-2-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q-02b_b7l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 11.815a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l4 3.5A5 5 0 0 1 21 11.815V21a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1ZM14 17a2 2 0 1 0-4 0v4h4Z");
}

.rrho5ub6z {
  d: path("M3 22a1 1 0 0 1 0-2h6v-3a3 3 0 1 1 6 0v3h6a1 1 0 0 1 0 2Zm10-2v-3a1 1 0 0 0-2 0v3Z");
}

</style>
