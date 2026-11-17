<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q8sy1lm9a"/><path class="u19ccl4ag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:excavator-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q8sy1lm9a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 15.171A3.001 3.001 0 0 1 13 21H5a3 3 0 1 1 0-6V8a1 1 0 0 1 1-1h3c.265 0 .52.105.707.293l4 4A1 1 0 0 1 14 12ZM7 9v3h4.586l-3-3Z");
}

.u19ccl4ag {
  d: path("M15.064 4.649a1 1 0 0 1 1.643-.356l5 5A1 1 0 0 1 22 10v5a1 1 0 0 1-1 1h-2a1 1 0 0 1-.894-.553l-1-2a1 1 0 0 1 .954-1.445a1 1 0 0 1 .834.551L19.618 14H20v-3.586l-3.609-3.609l-2.455 6.546a1 1 0 1 1-1.872-.702ZM4 15h10a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2");
}

</style>
