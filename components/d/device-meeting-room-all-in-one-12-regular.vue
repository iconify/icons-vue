<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="m0ak1nbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-all-in-one-12-regular" /></template>
<style>
.m0ak1nbqp {
  fill: currentColor;
  d: path("M6 4a.5.5 0 1 1 0 1a.5.5 0 0 1 0-1m2-2a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zM3 8a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1zm1-5a1 1 0 0 0-1 1v3h6V4a1 1 0 0 0-1-1z");
}

</style>
