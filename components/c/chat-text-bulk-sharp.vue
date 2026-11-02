<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jer5s5b2c"/><path class="vvs50ebqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-text-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jer5s5b2c {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 18H7.414l-3.707 3.707A1 1 0 0 1 2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1");
}

.vvs50ebqm {
  d: path("M16 7a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm-3 4a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Z");
}

</style>
