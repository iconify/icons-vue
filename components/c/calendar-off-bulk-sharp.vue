<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="eqsfz-9bw"/><path class="ce_lmpbfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-bulk-sharp" /></template>
<style>
.ce_lmpbfx {
  d: path("m21.293 22.707l-.824-.824A1 1 0 0 1 20 22H4a1 1 0 0 1-1-1V5c0-.164.04-.325.117-.469L1.293 2.707a.999.999 0 1 1 1.414-1.414l20 20a.999.999 0 1 1-1.414 1.414M11 6a1 1 0 0 1 0-2h4V3a1 1 0 0 1 2 0v1h3a1 1 0 0 1 1 1v9a1 1 0 0 1-2 0V6ZM5 20h13.586L5 6.414Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.eqsfz-9bw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m4 4l6 6H4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1m10.243 6l-6-6H20a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1Z");
}

</style>
