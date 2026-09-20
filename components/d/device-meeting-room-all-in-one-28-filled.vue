<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="bk8cmtbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-all-in-one-28-filled" /></template>
<style>
.bk8cmtbyt {
  fill: currentColor;
  d: path("M25 21.25A3.75 3.75 0 0 1 21.25 25H6.75A3.75 3.75 0 0 1 3 21.25V19.5h22zM21.25 3A3.75 3.75 0 0 1 25 6.75V18H3V6.75A3.75 3.75 0 0 1 6.75 3zM14 7a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3");
}

</style>
