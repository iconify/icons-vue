<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fumcxzb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bookmark-24-filled" /></template>
<style>
.fumcxzb6v {
  fill: currentColor;
  d: path("M6.19 21.855a.75.75 0 0 1-1.187-.61V6.25A3.25 3.25 0 0 1 8.253 3h7.498a3.25 3.25 0 0 1 3.25 3.25v14.996a.75.75 0 0 1-1.188.609l-5.81-4.181z");
}

</style>
