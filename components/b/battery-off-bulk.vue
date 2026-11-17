<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hku92c0dj"/><path class="okdait3_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hku92c0dj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 14.757L10.243 6H16a3 3 0 0 1 3 3ZM6 6l11.562 11.562A3 3 0 0 1 16 18H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3Z");
}

.okdait3_e {
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-20-20a.999.999 0 1 1 1.414-1.414M22 10v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

</style>
