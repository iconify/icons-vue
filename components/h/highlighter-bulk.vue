<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zfwfe1ezy"/><path class="uuraxgxqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:highlighter-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.uuraxgxqs {
  d: path("M4 17.414V19h3.586l3.707-3.707a.999.999 0 1 1 1.414 1.414l-4 4A1 1 0 0 1 8 21H4a2 2 0 0 1-2-2v-2c0-.265.105-.52.293-.707l5-5a.999.999 0 1 1 1.414 1.414Z");
}

.zfwfe1ezy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m6.293 10.293l6-6a2.414 2.414 0 0 1 3.414 0l4 4a2.414 2.414 0 0 1 0 3.414l-6 6a1 1 0 0 1-1.414 0l-6-6a.997.997 0 0 1 0-1.414");
}

</style>
