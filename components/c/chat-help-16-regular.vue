<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p31zvpder"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-help-16-regular" /></template>
<style>
.p31zvpder {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1-3.538 13.04l-2.804.935a.5.5 0 0 1-.633-.633l.934-2.806A7 7 0 0 1 8 1m0 1a6 6 0 0 0-5.07 9.207a.5.5 0 0 1 .052.426l-.692 2.075l2.076-.691c.15-.033.29-.034.426.052A6 6 0 1 0 8 2m0 8.5A.75.75 0 1 1 8 12a.75.75 0 0 1 0-1.5M8 4a2 2 0 0 1 2 2c0 .458-.125.803-.325 1.089c-.178.253-.426.463-.578.61c-.17.164-.309.318-.411.534c-.103.216-.186.528-.186 1.017a.5.5 0 0 1-1 0c0-.606.105-1.07.283-1.445a2.8 2.8 0 0 1 .62-.826c.222-.214.35-.316.453-.464C8.937 6.399 9 6.255 9 6a1 1 0 1 0-2 0a.5.5 0 1 1-1 0a2 2 0 0 1 2-2");
}

</style>
