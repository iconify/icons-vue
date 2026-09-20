<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zktljbb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-all-in-one-32-filled" /></template>
<style>
.zktljbb1x {
  fill: currentColor;
  d: path("M29 24.5a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5V22h26zM24.5 3A4.5 4.5 0 0 1 29 7.5V20H3V7.5A4.5 4.5 0 0 1 7.5 3zM16 8a2 2 0 1 0 0 4a2 2 0 0 0 0-4");
}

</style>
