<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ki64u0b_i"/><path class="qqm5c8b1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:column-minus-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ki64u0b_i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 4a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

.qqm5c8b1f {
  d: path("M14 11h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

</style>
