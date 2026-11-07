<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye5kct8ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-share-fill-round" /></template>
<style>
.ye5kct8ud {
  fill: currentColor;
  d: path("M2.954 16.131A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046l-4.673.935a1 1 0 0 1-1.177-1.177Zm13.753-4.838l-3-3a.999.999 0 1 0-1.414 1.414L13.586 11H11a3.98 3.98 0 0 0-2.828 1.172A3.98 3.98 0 0 0 7 15a1 1 0 0 0 2 0a2 2 0 0 1 2-2h2.586l-1.293 1.293a.999.999 0 1 0 1.414 1.414l3-3a1 1 0 0 0 0-1.414");
}

</style>
