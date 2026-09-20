<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kna9zbbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-bar-24-filled" /></template>
<style>
.kna9zbbfv {
  fill: currentColor;
  d: path("M15.251 17.5a.75.75 0 0 1 0 1.5H8.754a.75.75 0 0 1 0-1.5zm3.5-12.5a3.25 3.25 0 0 1 3.25 3.25v4.5a3.25 3.25 0 0 1-3.25 3.25H5.254a3.25 3.25 0 0 1-3.25-3.25v-4.5A3.25 3.25 0 0 1 5.254 5zM12 7.5a3 3 0 1 0 0 6a3 3 0 0 0 0-6M12 9a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m-6 .5a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
