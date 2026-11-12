<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y2yk23bwr"/><path class="wjclvfbbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gem-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wjclvfbbb {
  d: path("M10.707 10.293a.999.999 0 1 1-1.414 1.414l-2-2a.999.999 0 1 1 1.414-1.414Z");
}

.y2yk23bwr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m17.243 14.669l-3.831 4.257a1.9 1.9 0 0 1-2.824 0l-7.697-8.552a2 2 0 0 1 .073-2.752l2.743-2.743A3 3 0 0 1 7.828 4h8.344a3 3 0 0 1 2.121.879l2.743 2.743a2 2 0 0 1 .073 2.752Z");
}

</style>
