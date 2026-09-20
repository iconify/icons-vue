<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jo04zc6ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-checkmark-20-filled" /></template>
<style>
.jo04zc6ax {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1-3.613 15.14l-.121-.065l-3.645.91a.5.5 0 0 1-.62-.441v-.081l.014-.084l.91-3.644l-.064-.12a8 8 0 0 1-.828-2.886l-.025-.382L2 10a8 8 0 0 1 8-8m3.354 5.646a.5.5 0 0 0-.707 0L9 11.293L7.354 9.646a.5.5 0 1 0-.708.707l2 2a.5.5 0 0 0 .708 0l4-4a.5.5 0 0 0 0-.707");
}

</style>
