<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x7dwrjdbf"/><path class="dv5yto6iz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:award-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dv5yto6iz {
  d: path("M15.949 17.684c.13.392.182.805.152 1.217c-.054.772-.399 1.601-1.111 1.98c-.449.239-.983.24-1.437.013L12 20.118l-1.553.776a1.57 1.57 0 0 1-1.437-.013c-.712-.379-1.057-1.208-1.111-1.98a3.1 3.1 0 0 1 .152-1.217l1-3a1.001 1.001 0 0 1 1.898.632l-1 3a1.16 1.16 0 0 0-.032.608l1.636-.818a1 1 0 0 1 .894 0l1.636.818c.043-.2.033-.414-.032-.608l-1-3a1.001 1.001 0 0 1 1.898-.632Z");
}

.x7dwrjdbf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m15.14 15.258l.809 2.426c.13.392.182.805.152 1.217c-.054.772-.399 1.601-1.111 1.98c-.449.24-.983.24-1.437.013L12 20.118l-1.553.776a1.56 1.56 0 0 1-1.437-.013c-.712-.379-1.057-1.208-1.111-1.98a3.1 3.1 0 0 1 .152-1.217l.809-2.426A7.003 7.003 0 0 1 12 2a7.002 7.002 0 0 1 3.14 13.258");
}

</style>
