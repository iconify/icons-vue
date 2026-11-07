<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j51f5fbyv"/><path class="qred8bgyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-horizontal-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j51f5fbyv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.707 11.293l10 10a.999.999 0 1 1-1.414 1.414L11.586 13H8a1 1 0 0 1 0-2h1.586L1.293 2.707a.999.999 0 1 1 1.414-1.414Z");
}

.qred8bgyi {
  d: path("M7 9a3 3 0 1 0 0 6h2a1 1 0 0 1 0 2H7A5 5 0 0 1 7 7h1a1 1 0 0 1 0 2Zm10-2c1.33 0 2.597.522 3.536 1.464A4.98 4.98 0 0 1 22 12a4.97 4.97 0 0 1-.895 2.856a1 1 0 1 1-1.641-1.144A3.001 3.001 0 0 0 17 9h-2a1 1 0 0 1 0-2Z");
}

</style>
