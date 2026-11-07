<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4epp5b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-heart-fill-round" /></template>
<style>
.a4epp5b5l {
  fill: currentColor;
  d: path("M2.954 16.131A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046l-4.673.935a1 1 0 0 1-1.177-1.177ZM12 9.398A3.7 3.7 0 0 0 9.625 8.5C8.157 8.5 7 9.486 7 11c.001 1.964 2.294 3.6 3.871 4.52q.335.198.682.374a1 1 0 0 0 .894 0q.347-.176.682-.374q.763-.443 1.471-.97c1.103-.828 2.399-2.058 2.4-3.55c0-1.514-1.157-2.5-2.625-2.5c-.869 0-1.718.335-2.375.898");
}

</style>
