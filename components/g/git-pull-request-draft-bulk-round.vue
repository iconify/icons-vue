<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v_qg2hb2n"/><path class="j8yx7sbbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-pull-request-draft-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j8yx7sbbx {
  d: path("M19 5h.01a1 1 0 0 1 0 2H19a1 1 0 0 1 0-2M4 16V8a1 1 0 0 1 2 0v8a1 1 0 0 1-2 0m15-6h.01a1 1 0 0 1 0 2H19a1 1 0 0 1 0-2");
}

.v_qg2hb2n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m0 12a3 3 0 1 1 6 0a3 3 0 0 1-6 0m14 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
