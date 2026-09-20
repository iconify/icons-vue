<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w6mv3tbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-person-32-regular" /></template>
<style>
.w6mv3tbjm {
  fill: currentColor;
  d: path("M3 7.5A4.5 4.5 0 0 1 7.5 3h17A4.5 4.5 0 0 1 29 7.5V16a5 5 0 0 0-2-1.584V11H5v13.5A2.5 2.5 0 0 0 7.5 27h10.031c.078.695.302 1.375.68 2H7.5A4.5 4.5 0 0 1 3 24.5zM7.5 5A2.5 2.5 0 0 0 5 7.5V9h22V7.5A2.5 2.5 0 0 0 24.5 5zm21 14a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0m2.5 7.438c0 2.023-1.714 4.062-6 4.062s-6-2.031-6-4.062C19 25.102 20.082 24 21.417 24h7.166C29.918 24 31 25.102 31 26.438");
}

</style>
