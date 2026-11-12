<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yb1k0hbzc"/><path class="wjclvfbbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gem-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wjclvfbbb {
  d: path("M10.707 10.293a.999.999 0 1 1-1.414 1.414l-2-2a.999.999 0 1 1 1.414-1.414Z");
}

.yb1k0hbzc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 4c.265 0 .52.105.707.293l4 4a1 1 0 0 1 .036 1.376l-9 10a1 1 0 0 1-1.486 0l-9-10a1 1 0 0 1 .036-1.376l4-4A1 1 0 0 1 7 4Z");
}

</style>
