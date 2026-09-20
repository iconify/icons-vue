<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ucmpdrb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkbox-1-20-filled" /></template>
<style>
.ucmpdrb9b {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 2-.764v-.821a1.5 1.5 0 0 1-1.4-2.615l2-1.5q.187-.14.4-.214V6a3 3 0 0 0-3-3zm7.854 4.854l-5 5a.5.5 0 0 1-.708 0l-2-2a.5.5 0 0 1 .708-.708L8.5 11.793l4.646-4.647a.5.5 0 0 1 .708.708m3.87 4.199A.5.5 0 0 1 18 12.5v5a.5.5 0 0 1-1 0v-4l-1.2.9a.5.5 0 0 1-.6-.8l2-1.5a.5.5 0 0 1 .524-.047");
}

</style>
