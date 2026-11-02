<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h92vurbas"/><path class="evwqzz9yo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-yen-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.evwqzz9yo {
  d: path("m12 9.586l5.293-5.293a.999.999 0 1 1 1.414 1.414L13 11.414V19a1 1 0 0 1-2 0v-7.586L5.293 5.707a.999.999 0 1 1 1.414-1.414Z");
}

.h92vurbas {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 12h4a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm0 4h4a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Z");
}

</style>
