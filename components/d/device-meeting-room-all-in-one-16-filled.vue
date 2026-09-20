<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xkmqs8b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-all-in-one-16-filled" /></template>
<style>
.xkmqs8b0a {
  fill: currentColor;
  d: path("M14 11.5a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5V11h12zM11.5 2A2.5 2.5 0 0 1 14 4.5V10H2V4.5A2.5 2.5 0 0 1 4.5 2zM8 4.75a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5");
}

</style>
