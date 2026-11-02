<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u8sw8ofgw"/><path class="f-3gkjpyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-minus-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f-3gkjpyn {
  d: path("M9 8a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1Zm0 6h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

.u8sw8ofgw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 5a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

</style>
