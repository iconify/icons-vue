<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bjexm-byy"/><path class="o4ksy04tt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-help-corner-bulk-sharp" /></template>
<style>
.bjexm-byy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10h-9v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 6h4l-4-4Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.o4ksy04tt {
  d: path("M12 3a1.002 1.002 0 0 1 1.707-.707l6 6A1 1 0 0 1 19 10h-6a1 1 0 0 1-1-1Zm2 5h2.586L14 5.414Zm.236 6.832A3 3 0 1 1 17 19a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 16 16a1 1 0 0 1-2 0a3 3 0 0 1 .236-1.168M17.01 20a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Z");
}

</style>
