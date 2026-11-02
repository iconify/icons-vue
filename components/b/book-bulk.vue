<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tg4xjy-le"/><path class="ylauedbib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.tg4xjy-le {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 19V5a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H7a1 1 0 0 0-1 1a1 1 0 0 1-2 0");
}

.ylauedbib {
  d: path("M7 20h8a1 1 0 0 0 1-1v-2a1 1 0 0 1 2 0v2a3.004 3.004 0 0 1-3 3H7a2.998 2.998 0 0 1-2.597-4.501A3 3 0 0 1 7 16a1 1 0 0 1 0 2a1.002 1.002 0 0 0-.707 1.707A.97.97 0 0 0 7 20");
}

</style>
