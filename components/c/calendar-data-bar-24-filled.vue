<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr694xp4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-data-bar-24-filled" /></template>
<style>
.qr694xp4m {
  fill: currentColor;
  d: path("M21 8.5v4.55a2.5 2.5 0 0 0-1 .45a2.5 2.5 0 0 0-5 0v2a2.5 2.5 0 0 0-4 2V21H6.25A3.25 3.25 0 0 1 3 17.75V8.5zM17.75 3A3.25 3.25 0 0 1 21 6.25V7H3v-.75A3.25 3.25 0 0 1 6.25 3zm-.25 9a1.5 1.5 0 0 0-1.5 1.5v8a1.5 1.5 0 0 0 3 0v-8a1.5 1.5 0 0 0-1.5-1.5m-4 4a1.5 1.5 0 0 0-1.5 1.5v4a1.5 1.5 0 0 0 3 0v-4a1.5 1.5 0 0 0-1.5-1.5m6.5-.5a1.5 1.5 0 0 1 3 0v6a1.5 1.5 0 0 1-3 0z");
}

</style>
