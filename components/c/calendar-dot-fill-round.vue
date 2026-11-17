<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxvbbrrdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-dot-fill-round" /></template>
<style>
.rxvbbrrdq {
  fill: currentColor;
  d: path("M7 3a1 1 0 0 1 2 0v1h6V3a1 1 0 0 1 2 0v1.099A5.01 5.01 0 0 1 21 9v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5V9a5.01 5.01 0 0 1 4-4.901ZM5 17a3.004 3.004 0 0 0 3 3h8a3 3 0 0 0 3-3v-7H5Zm5-2a2 2 0 1 1 3.999-.001A2 2 0 0 1 10 15");
}

</style>
