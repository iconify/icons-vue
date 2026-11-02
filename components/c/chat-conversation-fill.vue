<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="heeg586ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-conversation-fill" /></template>
<style>
.heeg586ow {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H8c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 16.928 2 15.898 2 15Zm20 6v8c0 .898-.572 1.928-1.521 2.089a1.34 1.34 0 0 1-1.186-.382l-2-2C16.98 18.395 16.468 18 16 18H9a1 1 0 0 1 0-2h7c1.039 0 1.992.578 2.707 1.293L20 18.586V11a1 1 0 0 0-1-1a1 1 0 0 1 0-2a3 3 0 0 1 3 3");
}

</style>
