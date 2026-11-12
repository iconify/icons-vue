<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cr8at-bwx"/><path class="dbcpe3hqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:footprints-bulk-round" /></template>
<style>
.cr8at-bwx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 17a3 3 0 0 1-3 3h-1a3 3 0 0 1-3-3v-3a5.1 5.1 0 0 0-.261-1.621c-.259-.775-.68-1.482-1.017-2.223C13.26 9.138 13 8.131 13 7a6.1 6.1 0 0 1 .245-1.756C13.912 3.023 15.757 2 18 2c1.16 0 2.281.314 3.031 1.25C21.855 4.281 22 5.727 22 7ZM2 19V9c0-1.273.145-2.719.969-3.75C3.719 4.314 4.84 4 6 4c2.243 0 4.088 1.023 4.755 3.244A6.1 6.1 0 0 1 11 9c0 1.131-.26 2.138-.722 3.156c-.337.741-.758 1.448-1.017 2.223A5.1 5.1 0 0 0 9 16v3a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3");
}

.cuyn6tgcc {
  fill: currentColor;
}

.dbcpe3hqo {
  d: path("M22 16h-7v-2h7ZM9 16v2H2v-2Z");
}

</style>
