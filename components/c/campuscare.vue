<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c-epbv0qx"/><path class="mw5bke35b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:campuscare" /></template>
<style>
.c-epbv0qx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.634 26.136c2.585-6.776 11.307-4.84 11.307.648l-.32 11.627c-12.923 9.041-16.795-11.307 0-7.755m3.873-20.019c3.553-4.191 5.17-5.169 7.425-6.137m-8.722 5.818c-5.809 1.936-4.521-3.553-10.01-4.85c5.818-.968 7.754.978 10.01 4.85");
}

.mw5bke35b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.862 43.5C6.22 35.606 7.08 23.82 13.785 17.177s16.715-5.63 22.357 2.264c2.255 3.154 3.56 7.097 3.713 11.215c.449 13.223-13.233 15.18-13.233 7.754");
}

</style>
