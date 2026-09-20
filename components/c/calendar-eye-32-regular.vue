<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ljshr58jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-eye-32-regular" /></template>
<style>
.ljshr58jp {
  fill: currentColor;
  d: path("M23.5 17.5c4.142 0 7.5 4 7.5 6s-3.358 6-7.5 6s-7.5-4-7.5-6s3.358-6 7.5-6m1-14.5A4.5 4.5 0 0 1 29 7.5v10.464a10.3 10.3 0 0 0-2-1.19V11H5v13.5A2.5 2.5 0 0 0 7.5 27h8.442a10.7 10.7 0 0 0 2.012 2H7.5A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3zm-1 16.5a4 4 0 1 0 0 8a4 4 0 0 0 0-8m0 1.5a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5M7.5 5A2.5 2.5 0 0 0 5 7.5V9h22V7.5A2.5 2.5 0 0 0 24.5 5z");
}

</style>
