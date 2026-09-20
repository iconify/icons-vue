<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qbtz0bcpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-all-in-one-12-filled" /></template>
<style>
.qbtz0bcpl {
  fill: currentColor;
  d: path("M10 8a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2zM8 2a2 2 0 0 1 2 2v3H2V4a2 2 0 0 1 2-2zM6 4a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1");
}

</style>
