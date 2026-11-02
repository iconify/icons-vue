<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r0bcybc_h"/><path class="qqamo1bhx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-open-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qqamo1bhx {
  d: path("M8.707 13.293c.313.312.825.707 1.293.707h4c.468 0 .98-.395 1.293-.707l5-5a.999.999 0 1 1 1.414 1.414l-5 5C15.992 15.422 15.039 16 14 16h-4c-1.039 0-1.992-.578-2.707-1.293l-5-5a.999.999 0 1 1 1.414-1.414Z");
}

.r0bcybc_h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 22H5a3 3 0 0 1-3-3V9a1 1 0 0 1 .445-.832l6-4a6.41 6.41 0 0 1 7.11 0l6 4A1 1 0 0 1 22 9v10a3 3 0 0 1-3 3");
}

</style>
