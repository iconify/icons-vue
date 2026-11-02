<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uye652b5h"/><path class="g_0sa-bqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g_0sa-bqq {
  d: path("m2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414l-6.35-6.349c-.57.399-1.242.642-1.943.642a4 4 0 0 1-4-4c0-.701.243-1.373.642-1.943l-7.349-7.35a.999.999 0 1 1 1.414-1.414m9.776 12.604l-2.38-2.38A1.2 1.2 0 0 0 10 13a2 2 0 0 0 2 2c.166 0 .33-.037.483-.103");
}

.uye652b5h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 18.757L7.914 4.672l1.379-1.379A1 1 0 0 1 10 3h4c.265 0 .52.105.707.293L17.414 6H21a1 1 0 0 1 1 1ZM20 21H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1h2Z");
}

</style>
