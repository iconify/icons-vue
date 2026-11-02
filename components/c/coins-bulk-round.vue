<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="twxbyebhb"/><path class="gs1q52boj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coins-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gs1q52boj {
  d: path("M17.403 11.802L17.4 11.8a1 1 0 0 1 1.2-1.6l.07.053a6 6 0 1 1-8.393 8.448L10.2 18.6a1 1 0 0 1 1.478-1.335c.067.061.12.134.176.205a3.999 3.999 0 1 0 5.549-5.668");
}

.twxbyebhb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 9a6 6 0 1 1 12 0A6 6 0 0 1 3 9");
}

</style>
