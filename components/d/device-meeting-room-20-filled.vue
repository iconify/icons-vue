<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w815h55ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-20-filled" /></template>
<style>
.w815h55ru {
  fill: currentColor;
  d: path("M3.658 4.946A2.5 2.5 0 0 1 6.096 3h7.807a2.5 2.5 0 0 1 2.438 1.946l1.59 7A2.5 2.5 0 0 1 15.495 15H4.505a2.5 2.5 0 0 1-2.438-3.054zM5.5 16a.5.5 0 0 0 0 1h9a.5.5 0 1 0 0-1z");
}

</style>
