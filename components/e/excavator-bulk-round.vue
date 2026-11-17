<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e9uuvwbzv"/><path class="d1lfaybwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:excavator-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d1lfaybwd {
  d: path("M15.064 4.649a1 1 0 0 1 1.643-.356l4 4C21.422 9.008 22 9.961 22 11v3a2 2 0 0 1-2 2h-1a1 1 0 0 1-.894-.553l-1-2a1 1 0 0 1 .954-1.445a1 1 0 0 1 .834.551L19.618 14H20v-3c0-.468-.395-.98-.707-1.293l-2.902-2.902l-2.455 6.546a1 1 0 1 1-1.872-.702ZM4 15h10a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2");
}

.e9uuvwbzv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 15.171A3.001 3.001 0 0 1 13 21H5a3 3 0 1 1 0-6V9a2 2 0 0 1 2-2h1c1.039 0 1.992.578 2.707 1.293l2 2C13.422 11.008 14 11.961 14 13ZM8 9a1 1 0 0 0-1 1v2h4.586L8.879 9.293A1 1 0 0 0 8.172 9Z");
}

</style>
