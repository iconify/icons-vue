<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-q8_zbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:emoji-meh-24-regular" /></template>
<style>
.r-q8_zbny {
  fill: currentColor;
  d: path("M9 8.751a1.25 1.25 0 1 1 0 2.499a1.25 1.25 0 0 1 0-2.5m6 0a1.25 1.25 0 1 1 0 2.499a1.25 1.25 0 0 1 0-2.499M8.25 15a.75.75 0 0 0 0 1.5h7.5a.75.75 0 0 0 0-1.5zM2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12m10-8.5a8.5 8.5 0 1 0 0 17a8.5 8.5 0 0 0 0-17");
}

</style>
