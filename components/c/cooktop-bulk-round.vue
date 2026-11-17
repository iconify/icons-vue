<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yqxcxg4xa"/><path class="xll1gyu6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cooktop-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.xll1gyu6b {
  d: path("M5 7.997a3 3 0 1 1 6 0A3 3 0 0 1 5 8ZM7 8a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6.236-1.168a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338M17 8a1 1 0 1 0-2 0a1 1 0 0 0 2 0M5 15.997a3 3 0 1 1 6 0A3 3 0 0 1 5 16ZM7 16a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6.236-1.168a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338M17 16a1 1 0 1 0-2 0a1 1 0 0 0 2 0");
}

.yqxcxg4xa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Z");
}

</style>
