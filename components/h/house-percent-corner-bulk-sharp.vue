<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fn6lefoka"/><path class="ga07ohczk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-percent-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fn6lefoka {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.659 2.247l5.714 5A1.001 1.001 0 0 1 17.714 9H9v12a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10c0-.288.124-.563.341-.753l8-7c.378-.329.94-.329 1.318 0");
}

.ga07ohczk {
  d: path("M12.158 13.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m2.549 7.486a.999.999 0 1 1-1.414-1.414l6-6a.999.999 0 1 1 1.414 1.414Zm3.451-1.486a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
