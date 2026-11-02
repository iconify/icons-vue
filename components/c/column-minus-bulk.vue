<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gdrbqpbix"/><path class="qqm5c8b1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:column-minus-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gdrbqpbix {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

.qqm5c8b1f {
  d: path("M14 11h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

</style>
