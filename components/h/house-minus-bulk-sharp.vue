<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yssha6-2q"/><path class="lirtwccvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-minus-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lirtwccvs {
  d: path("M9 13h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

.yssha6-2q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.707 10.293A1 1 0 0 1 21 11v10a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V11c0-.265.105-.52.293-.707l8-8a1 1 0 0 1 1.414 0Z");
}

</style>
