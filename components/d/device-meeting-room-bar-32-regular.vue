<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z-5x6zbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-bar-32-regular" /></template>
<style>
.z-5x6zbbn {
  fill: currentColor;
  d: path("M21 24a1 1 0 1 1 0 2H11a1 1 0 1 1 0-2zm4.5-18a4.5 4.5 0 0 1 4.5 4.5v7a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 17.5v-7A4.5 4.5 0 0 1 6.5 6zm-19 2A2.5 2.5 0 0 0 4 10.5v7A2.5 2.5 0 0 0 6.5 20h19a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 25.5 8zM16 9.5a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m0 2a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5m-8 1a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

</style>
