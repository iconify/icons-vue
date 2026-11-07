<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e25vz7cbi"/><path class="r5revzb_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-help-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e25vz7cbi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.707 8.293A1 1 0 0 1 19 10h-6a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 4 17V7a5 5 0 0 1 5-5h4c.265 0 .52.105.707.293ZM13 6a2 2 0 0 0 2 2h2l-4-4Z");
}

.r5revzb_f {
  d: path("M12 3a1.002 1.002 0 0 1 1.707-.707l6 6A1 1 0 0 1 19 10h-4a3 3 0 0 1-3-3Zm2 4a.997.997 0 0 0 1 1h1.586L14 5.414Zm.236 7.832A3 3 0 1 1 17 19a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 16 16a1 1 0 0 1-2 0a3 3 0 0 1 .236-1.168M17.01 20a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Z");
}

</style>
