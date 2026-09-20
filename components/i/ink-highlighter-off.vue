<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xceafjmjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ink-highlighter-off" /></template>
<style>
.xceafjmjk {
  fill: currentColor;
  d: path("m15.779 12.935l-4.021-4.021l4.204-4.198q.484-.485 1.13-.485q.647 0 1.131.485l1.754 1.753q.485.485.485 1.131t-.485 1.13zm3.983 8.242l-6.116-6.115l-4.223 4.223q-.484.484-1.13.484q-.647 0-1.131-.484l-.204-.204l-1.15 1.15h-2.77l2.535-2.535l-.165-.165q-.485-.485-.485-1.131t.485-1.13l4.223-4.224L2.823 4.24l.714-.714l16.938 16.938z");
}

</style>
