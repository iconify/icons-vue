<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k5grhwt2m"/><path class="tx3i24bqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:atm-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k5grhwt2m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 10a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1Z");
}

.tx3i24bqq {
  d: path("M2 10V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-2 0v-6h-3a1 1 0 0 1 0-2h3V4H4v5h3a1 1 0 0 1 0 2H4v6a1 1 0 0 1-2 0Zm15-5a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm-7.764 9.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

</style>
