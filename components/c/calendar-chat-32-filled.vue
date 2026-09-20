<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r69m1zi6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-chat-32-filled" /></template>
<style>
.r69m1zi6p {
  fill: currentColor;
  d: path("M23 15.5a7.5 7.5 0 1 1-3.509 14.13l-3.365.858a.5.5 0 0 1-.608-.606l.853-3.37A7.5 7.5 0 0 1 23 15.5m6 .793a9 9 0 0 0-14.218 10.382L14.193 29H7.5A4.5 4.5 0 0 1 3 24.5V11h26zM20.25 24a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5zm0-3a.75.75 0 0 0 0 1.5h5.5a.75.75 0 0 0 0-1.5zM24.5 3A4.5 4.5 0 0 1 29 7.5V9H3V7.5A4.5 4.5 0 0 1 7.5 3z");
}

</style>
