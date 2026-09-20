<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="qd-4yjjst"/><path class="ef-n7kdoh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:caret-line-left-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ef-n7kdoh {
  d: path("M195.06 40.61a8 8 0 0 0-8.72 1.73l-80 80a8 8 0 0 0 0 11.32l80 80A8 8 0 0 0 200 208V48a8 8 0 0 0-4.94-7.39M184 188.69L123.31 128L184 67.31ZM80 48v160a8 8 0 0 1-16 0V48a8 8 0 0 1 16 0");
}

.qd-4yjjst {
  d: path("M192 48v160l-80-80Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
