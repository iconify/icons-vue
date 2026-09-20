<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="il-azebki"/><path class="z-p2nqf_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:currency-krw-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.il-azebki {
  d: path("M50 136h52l-26 64Zm52 0h52l-26-64Zm52 0l26 64l26-64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z-p2nqf_g {
  d: path("M240 128h-22.11l21.52-53a8 8 0 1 0-14.82-6l-24 59h-41.21l-24-59a8 8 0 0 0-14.82 0l-24 59H55.38l-24-59a8 8 0 0 0-14.82 6l21.52 53H16a8 8 0 0 0 0 16h28.61l24 59a8 8 0 0 0 14.82 0l24-59h41.24l24 59a8 8 0 0 0 14.82 0l24-59H240a8 8 0 0 0 0-16M76 178.75L61.88 144h28.24ZM113.88 128L128 93.26L142.12 128ZM180 178.75L165.88 144h28.24Z");
}

</style>
