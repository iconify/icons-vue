<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esc8_q6yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:grid-circles-24-filled" /></template>
<style>
.esc8_q6yg {
  fill: currentColor;
  d: path("M7 11a4 4 0 1 0 0-8a4 4 0 0 0 0 8m10 0a4 4 0 1 0 0-8a4 4 0 0 0 0 8m-6 6a4 4 0 1 1-8 0a4 4 0 0 1 8 0m6 4a4 4 0 1 0 0-8a4 4 0 0 0 0 8");
}

</style>
