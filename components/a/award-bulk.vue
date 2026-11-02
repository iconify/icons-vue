<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lgru9lpuk"/><path class="f9a_4n88r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:award-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f9a_4n88r {
  d: path("M16.949 20.684a.999.999 0 0 1-1.396 1.21L12 20.118l-3.553 1.776a.999.999 0 0 1-1.396-1.21l2-6a1.001 1.001 0 0 1 1.898.632l-1.237 3.71l1.841-.92a1 1 0 0 1 .894 0l1.841.92l-1.237-3.71a1.001 1.001 0 0 1 1.898-.632Z");
}

.lgru9lpuk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m15.14 15.258l1.809 5.426a.999.999 0 0 1-1.396 1.21L12 20.118l-3.553 1.776a.999.999 0 0 1-1.396-1.21l1.809-5.426A7.003 7.003 0 0 1 12 2a7.002 7.002 0 0 1 3.14 13.258");
}

</style>
