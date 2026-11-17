<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vab3u-aec"/><path class="xt8_web9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:laptop-user-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vab3u-aec {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 4a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

.xt8_web9c {
  d: path("M9 9a3 3 0 1 1 6 0a3 3 0 0 1-6 0m2 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m10 6a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h5.22c.236-.513.637-.935 1.104-1.246c1.513-1.009 3.839-1.009 5.352 0c.467.311.868.733 1.104 1.246ZM4 17v2h16v-2Z");
}

</style>
