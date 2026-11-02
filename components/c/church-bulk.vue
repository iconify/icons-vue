<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zhyyibcys"/><path class="bpia3acee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:church-bulk" /></template>
<style>
.bpia3acee {
  d: path("M13 4h1a1 1 0 0 1 0 2h-1v.586l3.707 3.707A1 1 0 0 1 17 11v10a1 1 0 0 1-2 0v-9.586l-3-3l-3 3V21a1 1 0 0 1-2 0V11c0-.265.105-.52.293-.707L11 6.586V6h-1a1 1 0 0 1 0-2h1V3a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.zhyyibcys {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.447 13.106c1.075.537 2.552 1.546 2.553 2.894v3a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-3c.001-1.348 1.478-2.357 2.553-2.894L7 12.382V11c0-.265.105-.52.293-.707l4-4a.997.997 0 0 1 1.414 0l4 4A1 1 0 0 1 17 11v1.382Z");
}

</style>
