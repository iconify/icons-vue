<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ssdm4pbde"/><path class="v8rzojtal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-phone-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ssdm4pbde {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 10h-7a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1H8a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5h8c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 21 9a1 1 0 0 1-1 1");
}

.v8rzojtal {
  d: path("M7 3a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0Zm8 0a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0ZM4 8h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m9.889 4h.444c.601 0 1.172.206 1.65.565c.477.358.835.845 1.057 1.397c.349.875.522 2.062-.182 2.815l.809.809c.531-.503 1.284-.697 2-.697h.444c.697 0 1.226.479 1.523 1.073c.264.528.366 1.119.366 1.705v.444A1.89 1.89 0 0 1 20.111 22a8 8 0 0 1-3.157-.638a8 8 0 0 1-2.578-1.738a8 8 0 0 1-1.738-2.578A8 8 0 0 1 12 13.889A1.89 1.89 0 0 1 13.889 12");
}

</style>
