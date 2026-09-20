<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="abcu5cb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-chat-32-regular" /></template>
<style>
.abcu5cb8g {
  fill: currentColor;
  d: path("M23 15.5a7.5 7.5 0 1 1-3.509 14.13l-3.365.858a.5.5 0 0 1-.608-.606l.853-3.37A7.5 7.5 0 0 1 23 15.5M24.5 3A4.5 4.5 0 0 1 29 7.5v8.793a9 9 0 0 0-2-1.355V11H5v13.5A2.5 2.5 0 0 0 7.5 27h7.2l-.507 2H7.5A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3zm-4.25 21a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5zm0-3a.75.75 0 0 0 0 1.5h5.5a.75.75 0 0 0 0-1.5zM7.5 5A2.5 2.5 0 0 0 5 7.5V9h22V7.5A2.5 2.5 0 0 0 24.5 5z");
}

</style>
