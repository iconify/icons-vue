<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ujqupuedv"/><path class="hzh37acaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-conversation-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hzh37acaj {
  d: path("M22 11v6c0 .926-.357 1.879-1.016 2.537c-.327.327-.732.577-1.193.655a1.69 1.69 0 0 1-1.498-.485l-1-1C16.735 18.15 15.737 18 15 18H9a1 1 0 0 1 0-2h6c1.313 0 2.749.335 3.707 1.293l.846.846C19.844 17.862 20 17.4 20 17v-6a1 1 0 0 0-1-1a1 1 0 0 1 0-2c.799 0 1.558.311 2.121.879A2.97 2.97 0 0 1 22 11");
}

.ujqupuedv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 13V7a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v2a5 5 0 0 1-5 5H9c-.749 0-1.737.152-2.293.707l-1 1a1.71 1.71 0 0 1-1.498.485c-.461-.078-.866-.328-1.193-.655a3.4 3.4 0 0 1-.732-1.116A3.7 3.7 0 0 1 2 13");
}

</style>
