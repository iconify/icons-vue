<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p-efwjxqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-area-32-regular" /></template>
<style>
.p-efwjxqp {
  fill: currentColor;
  d: path("M5 4a1 1 0 1 0-2 0v20.5A4.5 4.5 0 0 0 7.5 29H28a1 1 0 1 0 0-2h-2V9a1 1 0 0 0-1.6-.8l-7.506 5.63l-5.447-2.724a1 1 0 0 0-.84-.025L5 13.484zm0 11.66l5.968-2.558l5.585 2.792A1 1 0 0 0 17.6 15.8L24 11v16H7.5A2.5 2.5 0 0 1 5 24.5z");
}

</style>
