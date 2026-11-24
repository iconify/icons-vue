<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e25vz7cbi"/><path class="lvayi_drr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-shield-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e25vz7cbi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.707 8.293A1 1 0 0 1 19 10h-6a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 4 17V7a5 5 0 0 1 5-5h4c.265 0 .52.105.707.293ZM13 6a2 2 0 0 0 2 2h2l-4-4Z");
}

.lvayi_drr {
  d: path("M12 3a1 1 0 0 1 1.698-.716l.009.008v.001l6 6A1 1 0 0 1 19 10h-4a3 3 0 0 1-3-3Zm2 4a.997.997 0 0 0 1 1h1.586L14 5.414Zm6 5a2 2 0 0 1 2 2v2c-.001 3.075-1.94 4.852-4.629 5.928a1 1 0 0 1-.742 0C13.94 20.852 12.001 19.075 12 16v-2a2 2 0 0 1 2-2Z");
}

</style>
