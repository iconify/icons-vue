<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p1xfbteup"/><path class="d3o8jy_hq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:agent-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d3o8jy_hq {
  d: path("M13 5.733V9a1 1 0 0 1-2 0V5.733a2.001 2.001 0 1 1 2 0M8.986 14l.003-.001c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375l.001-.003a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177l.003.001a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375l-.001.003a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L8.986 16a1 1 0 0 1 0-2M5 16H3a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2m16-2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Z");
}

.p1xfbteup {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 11a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3Z");
}

</style>
