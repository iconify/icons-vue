<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t6x5jw7sa"/><path class="lrv276qwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:laptop-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lrv276qwq {
  d: path("M5 15h14a3 3 0 1 1 0 6H5a3 3 0 0 1 0-6m0 4h14a1 1 0 0 0 1-1v-.001A1 1 0 0 0 19 17H4.999A1 1 0 0 0 5 19");
}

.t6x5jw7sa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 17H5a1 1 0 0 1-1-1V6a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v10a1 1 0 0 1-1 1");
}

</style>
