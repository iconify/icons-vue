<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wlan7o2vb"/><path class="c2_bvub_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gift-bulk-sharp" /></template>
<style>
.c2_bvub_v {
  d: path("M9.707 3.293L12 5.586l2.293-2.293c.359-.36.798-.63 1.281-.789s.997-.209 1.497-.11a2.3 2.3 0 0 1 1.395.858C18.849 3.753 19 4.378 19 5c0 .421-.104.835-.305 1.205c-.432.809-1.239 1.331-2.102 1.583A5.7 5.7 0 0 1 15 8h-2v2h8a1 1 0 0 1 0 2h-8v9a1 1 0 0 1-2 0v-9H3a1 1 0 0 1 0-2h8V8H9a5.7 5.7 0 0 1-1.593-.212c-.863-.252-1.67-.774-2.102-1.583A2.5 2.5 0 0 1 5 5c0-.622.151-1.247.534-1.748a2.3 2.3 0 0 1 1.395-.858c.5-.099 1.015-.05 1.497.11c.483.159.922.429 1.281.789M14.414 6H15c.552 0 1.195-.084 1.65-.425c.185-.139.35-.332.35-.575c0-.252-.024-.585-.321-.644a.9.9 0 0 0-.472.046c-.188.062-.36.165-.5.305ZM8.293 4.707a1.3 1.3 0 0 0-.5-.305a.9.9 0 0 0-.472-.046C7.024 4.415 7 4.748 7 5c0 .243.165.436.35.575C7.805 5.916 8.448 6 9 6h.586Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.wlan7o2vb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6h18a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-1v9a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-9H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1");
}

</style>
