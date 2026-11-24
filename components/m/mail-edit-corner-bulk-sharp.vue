<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fwmd-xbaq"/><path class="jrwoi8o5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-edit-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fwmd-xbaq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 19V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H11v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1");
}

.jrwoi8o5n {
  d: path("M3.707 4.293L9.414 10h5.172l5.707-5.707a.999.999 0 1 1 1.414 1.414l-4.941 4.941l-.001.001l-1.058 1.058A1 1 0 0 1 15 12H9a1 1 0 0 1-.707-.293l-6-6a.999.999 0 1 1 1.414-1.414m9.586 13l4-4a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 17 22h-3a1 1 0 0 1-1-1v-3c0-.265.105-.52.293-.707");
}

</style>
