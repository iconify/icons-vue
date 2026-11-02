<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l5q2_7b2j"/><path class="h9wxoba2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-fork-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h9wxoba2a {
  d: path("M7 11h10a1 1 0 0 0 1-1V8a1 1 0 0 1 2 0v2a3 3 0 0 1-3 3h-4v3a1 1 0 0 1-2 0v-3H6.999c-.796 0-1.56-.317-2.122-.881A3 3 0 0 1 4 10V8a1 1 0 0 1 2 0v2a.997.997 0 0 0 1 1");
}

.l5q2_7b2j {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m14 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0M9 18a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
