<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9hv9-d7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-heart-fill" /></template>
<style>
.y9hv9-d7p {
  fill: currentColor;
  d: path("M8 18c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 20.928 2 19.898 2 19V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3Zm4-10.602A3.7 3.7 0 0 0 9.625 6.5C8.157 6.5 7 7.486 7 9c.001 1.964 2.294 3.6 3.871 4.52q.335.198.682.374a1 1 0 0 0 .894 0q.347-.176.682-.374q.763-.443 1.471-.97c1.103-.828 2.399-2.058 2.4-3.55c0-1.514-1.157-2.5-2.625-2.5c-.869 0-1.718.335-2.375.898");
}

</style>
