<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kxv0ujoic"/><path class="ezn9nz30l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ezn9nz30l {
  d: path("M7.707 9.293C8.263 9.848 9.252 10 10 10h4c.748 0 1.737-.152 2.293-.707l3-3a.999.999 0 1 1 1.414 1.414l-3 3C16.748 11.665 15.317 12 14 12h-4c-1.317 0-2.748-.335-3.707-1.293l-3-3a.999.999 0 1 1 1.414-1.414Z");
}

.kxv0ujoic {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 20H7a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20");
}

</style>
