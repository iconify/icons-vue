<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sfoflib8n"/><path class="l9_opmn8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l9_opmn8z {
  d: path("M19 10h-4a3 3 0 0 1-3-3V3a1.002 1.002 0 0 1 1.707-.707l6 6A1 1 0 0 1 19 10M2.707 3.293l18 18a.999.999 0 1 1-1.414 1.414l-18-18a.999.999 0 1 1 1.414-1.414M14 7a.997.997 0 0 0 1 1h1.586L14 5.414Z");
}

.sfoflib8n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 17.757L5.003 2.761A3 3 0 0 1 7 2h6c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9ZM13 7a2 2 0 0 0 2 2h3l-5-5Zm6.121 14.121A3 3 0 0 1 17 22H7a3 3 0 0 1-3-3V6Z");
}

</style>
