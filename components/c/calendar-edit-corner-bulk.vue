<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mepwg219h"/><path class="l7sbebb2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-edit-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l7sbebb2v {
  d: path("M7 3a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0Zm8 0a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0ZM4 8h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m8 13v-3c0-.265.105-.52.293-.707l5-5a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-5 5A1 1 0 0 1 16 22h-3a1 1 0 0 1-1-1");
}

.mepwg219h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 10h-9a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1");
}

</style>
