<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nflsbxo5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-cancel-32-regular" /></template>
<style>
.nflsbxo5b {
  fill: currentColor;
  d: path("M23 15.5a7.5 7.5 0 1 1 0 15a7.5 7.5 0 0 1 0-15M24.5 3A4.5 4.5 0 0 1 29 7.5v8.792a9 9 0 0 0-2-1.357V11H5v13.5A2.5 2.5 0 0 0 7.5 27h7.435c.362.728.82 1.4 1.357 2H7.5A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3zm2.28 16.22a.75.75 0 0 0-1.06 0L23 21.94l-2.72-2.72a.75.75 0 1 0-1.06 1.06L21.94 23l-2.72 2.72a.75.75 0 1 0 1.06 1.06L23 24.06l2.72 2.72a.75.75 0 1 0 1.06-1.06L24.06 23l2.72-2.72a.75.75 0 0 0 0-1.06M7.5 5A2.5 2.5 0 0 0 5 7.5V9h22V7.5A2.5 2.5 0 0 0 24.5 5z");
}

</style>
