<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp9q78bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:calendar-view-week-outline-sharp" /></template>
<style>
.vp9q78bzj {
  fill: currentColor;
  d: path("M13 18h2.5V6H13zm-4.5 0H11V6H8.5zM4 18h2.5V6H4zm13.5 0H20V6h-2.5zM2 20V4h20v16z");
}

</style>
