<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3r_-y69b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-checkmark-24-filled" /></template>
<style>
.b3r_-y69b {
  fill: currentColor;
  d: path("M11.733 9.5q.125.237.267.46v7.29A2.75 2.75 0 0 1 9.25 20h-4.5A2.75 2.75 0 0 1 2 17.25V9.5zM22 19.25a.75.75 0 0 1-1.5 0v-6.984a6.5 6.5 0 0 0 1.5-1.078zM5.75 12a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5zM17.5 1a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m3.354 3.146a.5.5 0 0 0-.707 0L16.5 7.793l-1.646-1.647a.5.5 0 1 0-.707.708l2 2a.5.5 0 0 0 .707 0l4-4a.5.5 0 0 0 0-.708M11.499 4a6.48 6.48 0 0 0-.323 4H2V6.25A2.25 2.25 0 0 1 4.25 4z");
}

</style>
