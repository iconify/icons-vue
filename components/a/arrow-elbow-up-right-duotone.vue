<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="uu9v0obbo"/><path class="ntm2hngll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-elbow-up-right-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ntm2hngll {
  d: path("m221.66 74.34l-48-48A8 8 0 0 0 160 32v40H72a8 8 0 0 0-8 8v144a8 8 0 0 0 16 0V88h80v40a8 8 0 0 0 13.66 5.66l48-48a8 8 0 0 0 0-11.32M176 108.69V51.31L204.69 80Z");
}

.uu9v0obbo {
  d: path("m216 80l-48 48V32Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
