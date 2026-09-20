<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cldl8orjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-help-16-filled" /></template>
<style>
.cldl8orjc {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1-3.538 13.04l-2.804.935a.5.5 0 0 1-.633-.633l.934-2.806A7 7 0 0 1 8 1m0 9.5A.75.75 0 1 0 8 12a.75.75 0 0 0 0-1.5M8 4a2 2 0 0 0-2 2a.5.5 0 0 0 1 0a1 1 0 0 1 2 0c0 .255-.063.4-.144.515c-.103.147-.23.25-.453.464a2.8 2.8 0 0 0-.62.826c-.178.375-.283.84-.283 1.445a.5.5 0 0 0 1 0c0-.489.083-.8.186-1.017c.102-.216.24-.37.41-.534c.153-.147.401-.357.579-.61c.2-.286.325-.631.325-1.089a2 2 0 0 0-2-2");
}

</style>
