<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i3_xuubtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:balcony-20-filled" /></template>
<style>
.i3_xuubtf {
  fill: currentColor;
  d: path("M17.6 8.01a.5.5 0 0 1 0 .98l-.1.01H17v5a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V9h-.5a.5.5 0 0 1 0-1h15zM14 14h2V9h-2zM4 14h2V9H4zm3 0h2.5V9H7zm3.5 0H13V9h-2.5zM12 2a3 3 0 0 1 3 3v2H5V5a3 3 0 0 1 3-3z");
}

</style>
