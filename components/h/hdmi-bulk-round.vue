<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="njmu03jqa"/><path class="f-8ytsblx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hdmi-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f-8ytsblx {
  d: path("M8 10h8a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2");
}

.njmu03jqa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 6a3 3 0 0 1 3 3v2a1 1 0 0 1-.168.555l-4 6A1 1 0 0 1 17 18H7a1 1 0 0 1-.832-.445l-4-6A1 1 0 0 1 2 11V9a3 3 0 0 1 3-3Z");
}

</style>
