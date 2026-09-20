<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d95-krwzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-24-filled" /></template>
<style>
.d95-krwzl {
  fill: currentColor;
  d: path("M4.093 5.346A3.06 3.06 0 0 1 7.07 3h9.858c1.416 0 2.647.97 2.979 2.346l1.992 8.273A3.55 3.55 0 0 1 18.448 18H5.553A3.55 3.55 0 0 1 2.1 13.62zM6.749 19a.75.75 0 1 0 0 1.5H17.25a.75.75 0 1 0 0-1.5z");
}

</style>
