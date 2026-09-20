<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="hocvxubud"/><path class="oqyw3hbgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:dot-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hocvxubud {
  d: path("M176 128a48 48 0 1 1-48-48a48 48 0 0 1 48 48");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oqyw3hbgk {
  d: path("M140 128a12 12 0 1 1-12-12a12 12 0 0 1 12 12");
}

</style>
