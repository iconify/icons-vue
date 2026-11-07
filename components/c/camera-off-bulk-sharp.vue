<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uye652b5h"/><path class="d8rmzsr4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d8rmzsr4b {
  d: path("m2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414l-6.261-6.261a4 4 0 0 1-5.478-5.478L1.293 3.707a.999.999 0 1 1 1.414-1.414m9.811 12.64l-2.451-2.451a2.004 2.004 0 0 0 2.451 2.451");
}

.uye652b5h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 18.757L7.914 4.672l1.379-1.379A1 1 0 0 1 10 3h4c.265 0 .52.105.707.293L17.414 6H21a1 1 0 0 1 1 1ZM20 21H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1h2Z");
}

</style>
