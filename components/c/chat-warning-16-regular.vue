<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qv2u_8bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-warning-16-regular" /></template>
<style>
.qv2u_8bkt {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1-3.538 13.04l-2.804.935a.5.5 0 0 1-.633-.633l.934-2.806A7 7 0 0 1 8 1m0 1a6 6 0 0 0-5.07 9.207a.5.5 0 0 1 .052.426l-.692 2.075l2.076-.691c.15-.033.29-.034.426.052A6 6 0 1 0 8 2m0 8a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5m0-5.5a.5.5 0 0 1 .492.41L8.5 5v3.5a.5.5 0 0 1-.992.09L7.5 8.5V5a.5.5 0 0 1 .5-.5");
}

</style>
