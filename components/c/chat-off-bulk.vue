<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="znug57hpo"/><path class="lk3mfzb5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lk3mfzb5t {
  d: path("M2.293 2.707a.999.999 0 1 1 1.414-1.414l19 19a.999.999 0 1 1-1.414 1.414Z");
}

.znug57hpo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.65 16.407L7.243 2H19a3 3 0 0 1 3 3v10c0 .49-.12.974-.35 1.407M3.438 2.438L19 18H8c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 20.928 2 19.898 2 19V5c0-1.047.544-2.018 1.438-2.562");
}

</style>
