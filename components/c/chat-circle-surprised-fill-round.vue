<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so_t371tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-surprised-fill-round" /></template>
<style>
.so_t371tv {
  fill: currentColor;
  d: path("M2.954 16.131A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046l-4.673.935a1 1 0 0 1-1.177-1.177ZM9 8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm6 0a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm-6 7a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
