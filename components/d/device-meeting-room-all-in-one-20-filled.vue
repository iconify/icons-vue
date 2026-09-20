<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tt-pcbbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-all-in-one-20-filled" /></template>
<style>
.tt-pcbbbv {
  fill: currentColor;
  d: path("M17 14a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-1h14zM14 3a3 3 0 0 1 3 3v6H3V6a3 3 0 0 1 3-3zm-4 3a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
