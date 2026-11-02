<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ssdm4pbde"/><path class="u8vnq8xqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-check-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ssdm4pbde {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 10h-7a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1H8a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5h8c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 21 9a1 1 0 0 1-1 1");
}

.u8vnq8xqc {
  d: path("M9 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM4 8h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m11.933 10.519l4.299-5.159a1 1 0 1 1 1.536 1.28l-5 6a1 1 0 0 1-1.475.067l-3-3a.999.999 0 1 1 1.414-1.414Z");
}

</style>
