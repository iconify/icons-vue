<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p5y-1qa5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-16-filled" /></template>
<style>
.p5y-1qa5n {
  fill: currentColor;
  d: path("M3 5.5A1.5 1.5 0 0 1 4.5 4h7A1.5 1.5 0 0 1 13 5.5v4a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 3 9.5zM2.5 12a.5.5 0 0 0 0 1h11a.5.5 0 0 0 0-1z");
}

</style>
