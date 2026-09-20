<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="g3_q4992k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-bar-12-filled" /></template>
<style>
.g3_q4992k {
  fill: currentColor;
  d: path("M7.5 9a.5.5 0 0 1 0 1h-3a.5.5 0 0 1 0-1zM9 2a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zM6 3.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m-3 1a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1m3 0a.5.5 0 1 1 0 1a.5.5 0 0 1 0-1");
}

</style>
