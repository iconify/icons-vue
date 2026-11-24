<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="byror8e2s"/><path class="lwpf5wbwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-warning-corner-bulk" /></template>
<style>
.byror8e2s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 10H11a.997.997 0 0 0-1 1v6a1 1 0 0 1-1 1H8c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 20.928 2 19.898 2 19V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v4a1 1 0 0 1-1 1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.lwpf5wbwd {
  d: path("M18 18a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Zm-.99 2a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Z");
}

</style>
