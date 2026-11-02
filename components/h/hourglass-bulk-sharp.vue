<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g27fl_nat"/><path class="a3chgg7oi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hourglass-bulk-sharp" /></template>
<style>
.a3chgg7oi {
  d: path("M5 2h14a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2m0 18h14a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.g27fl_nat {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 2h10a1 1 0 0 1 1 1v4c0 .265-.105.52-.293.707L13.414 12l4.293 4.293A1 1 0 0 1 18 17v4a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-4c0-.265.105-.52.293-.707L10.586 12L6.293 7.707A1 1 0 0 1 6 7V3a1 1 0 0 1 1-1");
}

</style>
