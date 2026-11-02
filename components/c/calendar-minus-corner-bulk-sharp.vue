<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wljdbqb8g"/><path class="dnw5rsc4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-minus-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dnw5rsc4p {
  d: path("M9 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM4 8h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m17 9h-8a1 1 0 0 1 0-2h8a1 1 0 0 1 0 2");
}

.wljdbqb8g {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 4h16a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H10v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1");
}

</style>
