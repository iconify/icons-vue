<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m8zax_b_t"/><path class="tdy0vw8yo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-conversation-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m8zax_b_t {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 15V5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H8c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 16.928 2 15.898 2 15");
}

.tdy0vw8yo {
  d: path("M22 11v8c0 .899-.571 1.928-1.521 2.089l-.004.001a1.36 1.36 0 0 1-1.182-.383l-2-2C16.976 18.39 16.468 18 16 18H9a1 1 0 0 1 0-2h7c1.039 0 1.991.577 2.707 1.293L20 18.586V11a1 1 0 0 0-1-1a1 1 0 0 1 0-2c.799 0 1.558.311 2.121.879A2.97 2.97 0 0 1 22 11");
}

</style>
