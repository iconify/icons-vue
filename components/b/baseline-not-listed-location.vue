<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zksxl5boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-not-listed-location" /></template>
<style>
.zksxl5boi {
  fill: currentColor;
  d: path("M12 2C8.14 2 5 5.14 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.86-3.14-7-7-7m.88 13.75h-1.75V14h1.75zm0-2.87h-1.75c0-2.84 2.62-2.62 2.62-4.38c0-.96-.79-1.75-1.75-1.75s-1.75.79-1.75 1.75H8.5C8.5 6.57 10.07 5 12 5s3.5 1.57 3.5 3.5c0 2.19-2.62 2.41-2.62 4.38");
}

</style>
