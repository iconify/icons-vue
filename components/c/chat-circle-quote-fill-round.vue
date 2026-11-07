<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-og7l1mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-quote-fill-round" /></template>
<style>
.r-og7l1mc {
  fill: currentColor;
  d: path("M2.954 16.131A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046l-4.673.935a1 1 0 0 1-1.177-1.177ZM10 9H8a1 1 0 0 0 0 2h1v.586l-1.707 1.707a.999.999 0 1 0 1.414 1.414l2-2A1 1 0 0 0 11 12v-2a1 1 0 0 0-1-1m6 0h-2a1 1 0 0 0 0 2h1v.586l-1.707 1.707a.999.999 0 1 0 1.414 1.414l2-2A1 1 0 0 0 17 12v-2a1 1 0 0 0-1-1");
}

</style>
