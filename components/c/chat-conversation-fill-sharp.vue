<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edoxrvblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-conversation-fill-sharp" /></template>
<style>
.edoxrvblx {
  fill: currentColor;
  d: path("M15 2a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H7.414l-3.707 3.707A1 1 0 0 1 2 17V3a1 1 0 0 1 1-1Zm6 6a1 1 0 0 1 1 1v12a1.002 1.002 0 0 1-1.707.707L16.586 18H9a1 1 0 0 1 0-2h8c.265 0 .52.105.707.293L20 18.586V10h-1a1 1 0 0 1 0-2Z");
}

</style>
