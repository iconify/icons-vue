<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cwapdcj5q"/><path class="wy5r0l0pi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-apartment-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cwapdcj5q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 4a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v17a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1Z");
}

.wy5r0l0pi {
  d: path("M10 7h.01a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2M9 20v-3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v3h1v-9a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V11a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v9Zm1-9h.01a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2m-8 1H4v8h2Zm14 8v-8h-2v8Zm-9 0h2v-2h-2Z");
}

</style>
