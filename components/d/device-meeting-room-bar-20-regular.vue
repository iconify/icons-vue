<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ga24l6-7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-bar-20-regular" /></template>
<style>
.ga24l6-7k {
  fill: currentColor;
  d: path("M13 14a.5.5 0 0 1 0 1H7a.5.5 0 0 1 0-1zm2-10a3 3 0 0 1 3 3v3a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3zM5 5a2 2 0 0 0-2 2v3a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V7a2 2 0 0 0-2-2zm5 1a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m0 1a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m-4.5.75a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5");
}

</style>
