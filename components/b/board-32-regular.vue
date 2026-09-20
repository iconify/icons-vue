<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u8_2s2bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:board-32-regular" /></template>
<style>
.u8_2s2bij {
  fill: currentColor;
  d: path("M24.5 3A4.5 4.5 0 0 1 29 7.5v17a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3zM5 24.5A2.5 2.5 0 0 0 7.5 27H15V12H5zM17 22v5h7.5a2.5 2.5 0 0 0 2.5-2.5V22zm0-2h10V7.5A2.5 2.5 0 0 0 24.5 5H17zM7.5 5A2.5 2.5 0 0 0 5 7.5V10h10V5z");
}

</style>
