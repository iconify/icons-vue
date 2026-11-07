<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak5r4vsrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-text-fill" /></template>
<style>
.ak5r4vsrj {
  fill: currentColor;
  d: path("M2.954 16.131A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046l-4.673.935a1 1 0 0 1-1.177-1.177ZM8 9a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Zm5 4H8a1 1 0 0 0 0 2h5a1 1 0 0 0 0-2");
}

</style>
