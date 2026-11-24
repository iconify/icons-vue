<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bjexm-byy"/><path class="guoez4fjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-percent-corner-bulk-sharp" /></template>
<style>
.bjexm-byy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10h-9v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 6h4l-4-4Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.guoez4fjj {
  d: path("M12 3a1.002 1.002 0 0 1 1.707-.707l6 6A1 1 0 0 1 19 10h-6a1 1 0 0 1-1-1Zm2 5h2.586L14 5.414Zm-1.842 5.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m2.549 7.486a.999.999 0 1 1-1.414-1.414l6-6a.999.999 0 1 1 1.414 1.414Zm3.451-1.486a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
