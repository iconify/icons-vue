<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pm6c1nrms"/><path class="ztu8b7qfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pm6c1nrms {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 17.757L4.425 2.182C4.593 2.064 4.794 2 5 2h8c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9ZM13 9h5l-5-5ZM4 6l15.707 15.707A1 1 0 0 1 19 22H5a1 1 0 0 1-1-1Z");
}

.ztu8b7qfc {
  d: path("M19 10h-6a1 1 0 0 1-1-1V3a1.002 1.002 0 0 1 1.707-.707l6 6A1 1 0 0 1 19 10M2.707 3.293l18 18a.999.999 0 1 1-1.414 1.414l-18-18a.999.999 0 1 1 1.414-1.414M14 8h2.586L14 5.414Z");
}

</style>
