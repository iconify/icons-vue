<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lhrhq1bxr"/><path class="ajazqupgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-bulk" /></template>
<style>
.ajazqupgq {
  d: path("m4.293 4.879l4.414 4.414c.315.315.825.707 1.293.707h4c.468 0 .976-.39 1.293-.707l4.414-4.414a.999.999 0 1 1 1.414 1.414l-4.414 4.414C15.991 11.423 15.039 12 14 12h-4c-1.039 0-1.991-.577-2.707-1.293L2.879 6.293a.999.999 0 1 1 1.414-1.414");
}

.cuyn6tgcc {
  fill: currentColor;
}

.lhrhq1bxr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 20H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3");
}

</style>
