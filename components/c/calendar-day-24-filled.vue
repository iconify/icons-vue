<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9ointlmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-day-24-filled" /></template>
<style>
.u9ointlmt {
  fill: currentColor;
  d: path("M17.75 3A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zm-1.5 8h-8.5a.75.75 0 0 0-.743.648L7 11.75v4.5c0 .38.282.694.648.743L7.75 17h8.5a.75.75 0 0 0 .743-.648L17 16.25v-4.5a.75.75 0 0 0-.648-.743zm-.75 1.5v3h-7v-3zm.75-5.25h-8.5a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5");
}

</style>
