<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xplp402pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-person-32-filled" /></template>
<style>
.xplp402pq {
  fill: currentColor;
  d: path("M3 7.5A4.5 4.5 0 0 1 7.5 3h17A4.5 4.5 0 0 1 29 7.5V9H3zM3 11h26v5a5 5 0 1 0-7.57 6.5h-.013c-2.18 0-3.917 1.79-3.917 3.938c0 .886.231 1.77.71 2.562H7.5A4.5 4.5 0 0 1 3 24.5zm25.5 8a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0m2.5 7.438c0 2.023-1.714 4.062-6 4.062s-6-2.031-6-4.062C19 25.102 20.082 24 21.417 24h7.166C29.918 24 31 25.102 31 26.438");
}

</style>
