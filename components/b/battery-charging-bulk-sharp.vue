<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dyo4c8bkh"/><path class="v-6q2uxkc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-charging-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dyo4c8bkh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a1 1 0 0 1 1-1h15a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.v-6q2uxkc {
  d: path("m11.707 10.707l-.293.293H12a1.002 1.002 0 0 1 .707 1.707l-2 2a.999.999 0 1 1-1.414-1.414L9.586 13H9a1.002 1.002 0 0 1-.707-1.707l2-2a.999.999 0 1 1 1.414 1.414M22 14a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Z");
}

</style>
