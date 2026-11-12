<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a4clcdbsf"/><path class="zp_nyr2da"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:combobox-bulk-sharp" /></template>
<style>
.a4clcdbsf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2h18a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1m0 12h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.zp_nyr2da {
  d: path("M8 8a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0Zm8-1.414l1.293-1.293a.999.999 0 1 1 1.414 1.414l-2 2a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414ZM7 17h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

</style>
