<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s1qnp3wqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-warning-16-filled" /></template>
<style>
.s1qnp3wqc {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1-3.538 13.04l-2.804.935a.5.5 0 0 1-.633-.633l.934-2.806A7 7 0 0 1 8 1m0 9a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5m0-5.5a.5.5 0 0 0-.5.5v3.5l.008.09A.5.5 0 0 0 8.5 8.5V5l-.008-.09A.5.5 0 0 0 8 4.5");
}

</style>
