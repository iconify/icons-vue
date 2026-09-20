<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ya0ppmb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-all-in-one-28-regular" /></template>
<style>
.ya0ppmb9j {
  fill: currentColor;
  d: path("M14 7a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m7.25-4A3.75 3.75 0 0 1 25 6.75v14.5A3.75 3.75 0 0 1 21.25 25H6.75A3.75 3.75 0 0 1 3 21.25V6.75A3.75 3.75 0 0 1 6.75 3zM4.5 21.25a2.25 2.25 0 0 0 2.25 2.25h14.5a2.25 2.25 0 0 0 2.25-2.25V19.5h-19zM6.75 4.5A2.25 2.25 0 0 0 4.5 6.75V18h19V6.75a2.25 2.25 0 0 0-2.25-2.25z");
}

</style>
