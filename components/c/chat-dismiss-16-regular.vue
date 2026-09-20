<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x22_kqb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-dismiss-16-regular" /></template>
<style>
.x22_kqb6w {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1-3.538 13.04l-2.804.935a.5.5 0 0 1-.633-.633l.934-2.806A7 7 0 0 1 8 1m0 1a6 6 0 0 0-5.07 9.207a.5.5 0 0 1 .052.426l-.692 2.075l2.076-.691c.15-.033.29-.034.426.052A6 6 0 1 0 8 2m1.646 3.646a.5.5 0 0 1 .707.708L8.708 8l1.646 1.647a.5.5 0 0 1-.707.707L8 8.707l-1.647 1.646a.5.5 0 0 1-.707-.706L7.293 8L5.646 6.354a.5.5 0 0 1 .707-.708L8 7.294z");
}

</style>
